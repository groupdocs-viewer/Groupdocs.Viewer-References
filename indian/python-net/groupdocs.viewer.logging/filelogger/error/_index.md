---
title: "error मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "कंसोल में एक त्रुटि संदेश लिखता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

कंसोल में एक त्रुटि संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं की जानकारी प्रदान करते हैं।

```python
def error(self, message, exception):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| message | `str` | त्रुटि संदेश। |
| exception | `Exception` | अपवाद। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `exception` None है। |

### साथ में देखें
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
