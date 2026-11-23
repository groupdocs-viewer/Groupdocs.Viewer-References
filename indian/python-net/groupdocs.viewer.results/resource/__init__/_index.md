---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया Resource उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

एक नया Resource उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

एक नया Resource उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_name, nested):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_name | `str` | संसाधन फ़ाइल नाम। |
| nested | `bool` | यह दर्शाता है कि क्या संसाधन किसी अन्य संसाधन के भीतर स्थित है, उदाहरण के लिए फ़ॉन्ट संसाधन जो CSS या SVG संसाधन में स्थित है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `file_name` जब None या खाली हो तो उत्पन्न होता है। |

### साथ में देखें
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
