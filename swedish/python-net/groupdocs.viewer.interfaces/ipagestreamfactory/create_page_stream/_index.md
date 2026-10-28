---
title: "create_page_stream-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skapar strömmen som används för att skriva utdata för siddata."
type: docs
url: /sv/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Skapar strömmen som används för att skriva utdata för siddata.

```python
def create_page_stream(self, page_number):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Exempel

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

### Se även
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
