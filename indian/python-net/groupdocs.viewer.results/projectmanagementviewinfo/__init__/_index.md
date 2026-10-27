---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ProjectManagementViewInfo का नया उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

एक नया उदाहरण प्रारंभ करता है [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) का।

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

ProjectManagementViewInfo का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_type | `FileType` | फ़ाइल का प्रकार। |
| pages | `List[Page]` | देखने के लिए पृष्ठों की सूची। |
| start_date | `datetime` | प्रोजेक्ट के शुरू होने की तिथि और समय। |
| end_date | `datetime` | प्रोजेक्ट के पूर्ण होने की तिथि और समय। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `pages` None है। |

### साथ में देखें
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
