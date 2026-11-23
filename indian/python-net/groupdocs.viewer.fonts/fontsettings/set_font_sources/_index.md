---
title: "set_font_sources मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "दस्तावेज़ रेंडर करते समय TrueType फ़ॉन्ट खोजने के लिए स्रोत सेट करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

दस्तावेज़ रेंडर करते समय TrueType फ़ॉन्ट खोजने के लिए स्रोत सेट करता है।

यह मेथड व्यक्तिगत [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) ऑब्जेक्ट्स, उनके सूचियों, या दोनों के मिश्रण के किसी भी संयोजन को स्वीकार करता है; सभी इनपुट को लागू करने से पहले एक एकल सूची में समतल किया जाता है। स्ट्रिंग पाथ को जैसा है वैसा ही पास किया जाता है और उन्हें अक्षरों में विभाजित नहीं किया जाता।

```python
def set_font_sources(cls, font_sources):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | फ़ॉन्ट स्रोत। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | `font_sources` जब None हो। |

### उदाहरण

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# एकल सूची
FontSettings.set_font_sources([src1, src2])
# एकाधिक सूचियाँ (समतल की गई)
FontSettings.set_font_sources([src1], [src2])
# मिश्रित — भी समतल की गई
FontSettings.set_font_sources([src1, src2], src2)
```

### साथ में देखें
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
