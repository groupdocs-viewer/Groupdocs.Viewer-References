---
title: "get_view_info मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "व्यू और दस्तावेज़ विशिष्ट जानकारी लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

व्यू और दस्तावेज़ विशिष्ट जानकारी लौटाता है।

दस्तावेज़ के बारे में अधिक जानें - फ़ाइल प्रकार, पृष्ठों की संख्या और अन्य फ़ॉर्मेट-विशिष्ट गुण:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `ViewInfoOptions` | व्यू इन्फो विकल्प। |

**Returns:** Information about view and document specific information.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `options` None है। |
| `PasswordRequiredException` | जब दस्तावेज़ खोलने के लिए पासवर्ड आवश्यक होता है। |
| `IncorrectPasswordException` | जब निर्दिष्ट पासवर्ड गलत होता है। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### साथ में देखें
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
