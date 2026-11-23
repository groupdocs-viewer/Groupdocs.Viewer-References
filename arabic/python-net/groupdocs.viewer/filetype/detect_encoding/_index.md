---
title: "طريقة detect_encoding"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يكشف عن ترميز ملفات النص TXT و TSV و CSV حسب المسار."
type: docs
url: /ar/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

يكشف عن ترميز ملفات النص TXT و TSV و CSV حسب المسار.

```python
def detect_encoding(cls, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | اسم الملف أو مسار الملف. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### مثال

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

يحاول الكشف عن ترميز ملفات النص (TXT، TSV، CSV) من تدفق.

```python
def detect_encoding(cls, stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### مثال

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### انظر أيضًا
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
