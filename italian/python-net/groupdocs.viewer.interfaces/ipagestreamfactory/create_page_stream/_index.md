---
title: "metodo create_page_stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Crea il flusso utilizzato per scrivere i dati della pagina di output."
type: docs
url: /it/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Crea il flusso utilizzato per scrivere i dati della pagina di output.

```python
def create_page_stream(self, page_number):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero di una pagina. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Esempio

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### Vedi anche
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
