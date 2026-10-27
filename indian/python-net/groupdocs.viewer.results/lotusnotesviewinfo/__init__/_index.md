---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "LotusNotesViewInfo का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

[`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

[`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) क्लास का नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_type | `FileType` | फ़ाइल का प्रकार। |
| pages | `List[Page]` | देखने के लिए पृष्ठों की सूची। |
| notes_count | `int` | Lotus डेटाबेस स्टोरेज फ़ाइल में शामिल नोट्स की गिनती। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `notes_count` None हो, तो उत्पन्न होता है। |

### साथ में देखें
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
