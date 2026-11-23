---
title: "FolderFontSource क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "TrueType फ़ॉन्ट्स वाले फ़ोल्डर का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

TrueType फ़ॉन्ट्स वाले फ़ोल्डर का प्रतिनिधित्व करता है।

FolderFontSource प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | एक नया उदाहरण प्रारंभ करता है [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) का। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट FolderFontSource ऑब्जेक्ट के समान है या नहीं। |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट ऑब्जेक्ट के समान है या नहीं। |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | वर्तमान [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | एक स्ट्रिंग लौटाता है जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | फ़ोल्डर का पथ जो TrueType फ़ॉन्ट्स रखता है। |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | खोज विकल्प जो निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए, या वर्तमान फ़ोल्डर और सभी उपफ़ोल्डर। |

### उदाहरण

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# एक फ़ॉन्ट स्रोत बनाएं जो सभी उपफ़ोल्डरों को खोजता है।
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
