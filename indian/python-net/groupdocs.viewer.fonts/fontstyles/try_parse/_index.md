---
title: "try_parse मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "निर्दिष्ट कच्ची स्ट्रिंग को फ़ॉन्ट शैली नाम के रूप में पार्स करने का प्रयास करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

निर्दिष्ट कच्ची स्ट्रिंग को फ़ॉन्ट शैली नाम के रूप में पार्स करने का प्रयास करता है।

```python
def try_parse(cls, style, parsed):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| style | `str` | फ़ॉन्ट स्टाइल के रूप में पार्स की जानी चाहिए ऐसी स्ट्रिंग। |
| parsed | `FontStyles` | सफलता पर पार्स किया गया फ़ॉन्ट स्टाइल या विफलता पर `FontStyles.Regular`। |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### साथ में देखें
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
