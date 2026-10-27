---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "FolderFontSource का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

एक नया उदाहरण प्रारंभ करता है [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) का।

```python
def __init__(self, folder_path, search_option):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| folder_path | `str` | TrueType फ़ॉन्ट्स वाले फ़ोल्डर का पथ। |
| search_option | `SearchOption` | निर्दिष्ट करता है कि केवल वर्तमान फ़ोल्डर खोजा जाए या वर्तमान फ़ोल्डर और सभी सब‑फ़ोल्डर। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `folder_path` None है। |
| `FileNotFoundError` | यदि `folder_path` में निर्दिष्ट पथ नहीं मिला। |

### उदाहरण

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# रेंडरिंग के लिए फ़ॉन्ट स्रोतों को रजिस्टर करें
FontSettings.set_font_sources(src1, src2)

# काम समाप्त होने पर, स्रोतों के लीक होने से बचने के लिए रीसेट करें
FontSettings.reset_font_sources()
```

### साथ में देखें
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
