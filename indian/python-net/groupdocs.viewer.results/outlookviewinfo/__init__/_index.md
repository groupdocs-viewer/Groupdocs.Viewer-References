---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "OutlookViewInfo का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

एक नया उदाहरण प्रारंभ करता है [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) का।

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

एक नया OutlookViewInfo उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_type, pages, folders):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_type | `FileType` | फ़ाइल का प्रकार। |
| pages | `List[Page]` | देखने के लिए पृष्ठों की सूची। |
| folders | `List[str]` | Outlook Data फ़ाइल में शामिल फ़ोल्डर्स की सूची। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `folders` None होने पर फेंका जाता है। |

### साथ में देखें
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
