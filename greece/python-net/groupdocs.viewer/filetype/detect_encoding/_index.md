---
title: "μέθοδος detect_encoding"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ανιχνεύει την κωδικοποίηση των αρχείων κειμένου TXT, TSV και CSV με βάση τη διαδρομή."
type: docs
url: /el/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Ανιχνεύει την κωδικοποίηση των αρχείων κειμένου TXT, TSV και CSV με βάση τη διαδρομή.

```python
def detect_encoding(cls, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Το όνομα αρχείου ή η διαδρομή αρχείου. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Παράδειγμα

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Προσπαθεί να ανιχνεύσει την κωδικοποίηση των αρχείων κειμένου (TXT, TSV, CSV) από μια ροή.

```python
def detect_encoding(cls, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Παράδειγμα

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Δείτε επίσης
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
