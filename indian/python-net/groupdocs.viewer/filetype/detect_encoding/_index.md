---
title: "detect_encoding मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "पथ द्वारा टेक्स्ट TXT, TSV, और CSV फ़ाइलों की एन्कोडिंग का पता लगाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

पथ द्वारा टेक्स्ट TXT, TSV, और CSV फ़ाइलों की एन्कोडिंग का पता लगाता है।

```python
def detect_encoding(cls, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल का नाम या फ़ाइल पथ। |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### उदाहरण

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

स्ट्रीम से टेक्स्ट फ़ाइलों (TXT, TSV, CSV) की एन्कोडिंग का पता लगाने का प्रयास करता है।

```python
def detect_encoding(cls, stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### उदाहरण

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### साथ में देखें
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
