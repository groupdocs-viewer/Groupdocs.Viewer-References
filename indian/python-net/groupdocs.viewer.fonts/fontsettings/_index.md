---
title: "FontSettings क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "TrueType फ़ॉन्ट्स खोजने के लिए स्रोतों के साथ काम करने के लिए मेथड प्रदान करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

TrueType फ़ॉन्ट्स खोजने के लिए स्रोतों के साथ काम करने के लिए मेथड प्रदान करता है।

FontSettings प्रकार निम्नलिखित सदस्य प्रदर्शित करता है:

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | पहले सेट किए गए फ़ॉन्ट स्रोतों को रीसेट करता है। |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | दस्तावेज़ रेंडर करते समय TrueType फ़ॉन्ट खोजने के लिए स्रोत सेट करता है। |

### उदाहरण

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# विभिन्न तर्क रूपों का उपयोग करके फ़ॉन्ट स्रोत सेट करें (आंतरिक रूप से फ्लैटन किया गया)।
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# सभी पंजीकृत फ़ॉन्ट स्रोतों को साफ़ करें।
FontSettings.reset_font_sources()
```

### साथ में देखें
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
