---
title: detect_encoding method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Detects the encoding of text TXT, TSV, and CSV files by path."
type: docs
url: /python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Detects the encoding of text TXT, TSV, and CSV files by path.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file name or file path. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Example

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Attempts to detect the encoding of text files (TXT, TSV, CSV) from a stream.

```python
def detect_encoding(cls, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Example

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### See Also
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
