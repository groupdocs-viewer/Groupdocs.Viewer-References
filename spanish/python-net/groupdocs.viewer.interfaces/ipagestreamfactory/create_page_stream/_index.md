---
title: "método create_page_stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Crea el flujo utilizado para escribir los datos de página de salida."
type: docs
url: /es/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Crea el flujo utilizado para escribir los datos de página de salida.

```python
def create_page_stream(self, page_number):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de una página. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Ejemplo

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

### Ver también
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
