---
title: "for_jpg_view मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "JPG में रेंडर करते समय व्यू की जानकारी प्राप्त करने के लिए एक ViewInfoOptions इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

JPG में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए एक [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) इंस्टेंस को प्रारंभ करता है।

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

JPG में रेंडर करते समय दृश्य जानकारी प्राप्त करने के लिए एक ViewInfoOptions इंस्टेंस को प्रारंभ करता है।

```python
def for_jpg_view(cls, extract_text):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| extract_text | `bool` | टेक्स्ट एक्सट्रैक्शन सक्षम करता है। |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### साथ में देखें
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
