---
title: "create_page_stream-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Maakt de stream aan die wordt gebruikt om uitvoerpagina‑gegevens te schrijven."
type: docs
url: /nl/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Maakt de stream aan die wordt gebruikt om uitvoerpagina‑gegevens te schrijven.

```python
def create_page_stream(self, page_number):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het paginanummer. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Voorbeeld

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

### Zie ook
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
