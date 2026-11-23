---
title: "detect_encoding-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Detekterar kodningen för textfiler TXT, TSV och CSV via sökväg."
type: docs
url: /sv/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Detekterar kodningen för textfiler TXT, TSV och CSV via sökväg.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filnamnet eller filsökvägen. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Exempel

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Försöker detektera kodningen för textfiler (TXT, TSV, CSV) från en ström.

```python
def detect_encoding(cls, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Exempel

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Se även
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
