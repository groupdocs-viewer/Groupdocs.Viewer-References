---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "LoadOptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) क्लास का एक उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

एक नया LoadOptions उदाहरण प्रारंभ करता है।

कोड उदाहरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, file_type):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_type | `FileType` | खोलने वाली फ़ाइल का प्रकार। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `file_type` None है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### साथ में देखें
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
