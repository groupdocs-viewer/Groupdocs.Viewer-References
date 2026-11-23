---
title: "create_page_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Erstellt den Stream, der zum Schreiben der Ausgabeseitendaten verwendet wird."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Erstellt den Stream, der zum Schreiben der Ausgabeseitendaten verwendet wird.

```python
def create_page_stream(self, page_number):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Nummer einer Seite. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Beispiel

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

### Siehe auch
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
