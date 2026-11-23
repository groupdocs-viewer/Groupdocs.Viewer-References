---
title: "create_page_stream मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम बनाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

आउटपुट पेज डेटा लिखने के लिए उपयोग की जाने वाली स्ट्रीम बनाता है।

```python
def create_page_stream(self, page_number):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | एक पृष्ठ की संख्या। |

**Returns:** io.RawIOBase: Stream used to write output page data.

### उदाहरण

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

### साथ में देखें
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
