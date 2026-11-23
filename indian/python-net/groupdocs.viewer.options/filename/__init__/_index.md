---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "FileName क्लास का एक इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

एक [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) क्लास का इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, file_name):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_name | `str` | फ़ाइल का नाम। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `file_name` None है। |

### उदाहरण

```python
from groupdocs.viewer.options import FileName

# कस्टम आर्काइव नाम के साथ एक FileName इंस्टेंस बनाएं
custom_name = FileName("Sample Files")
```

### साथ में देखें
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
