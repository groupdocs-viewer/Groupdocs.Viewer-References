---
title: "set_license मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्तमान प्रक्रिया में लाइसेंस लागू करें।"
type: docs
url: /hi/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

वर्तमान प्रक्रिया में लाइसेंस लागू करें।

```python
def set_license(self, license_source):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| license_source |  | या तो एक स्ट्रिंग पथ जो ``.lic`` फ़ाइल की ओर इशारा करता है या एक पढ़ने योग्य फ़ाइल‑समान ऑब्जेक्ट जो लाइसेंस बाइट्स देता है। फ़ाइल‑समान इनपुट को ब्रिज को पास करने से पहले एक अस्थायी फ़ाइल में लिखा जाता है। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `TypeError` | यदि ``license_source`` न तो एक स्ट्रिंग पथ है और न ही एक पढ़ने योग्य फ़ाइल‑समान ऑब्जेक्ट है। |

### साथ में देखें
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
