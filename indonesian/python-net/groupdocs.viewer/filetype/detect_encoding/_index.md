---
title: "metode detect_encoding"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mendeteksi enkoding file teks TXT, TSV, dan CSV berdasarkan path."
type: docs
url: /id/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Mendeteksi enkoding file teks TXT, TSV, dan CSV berdasarkan path.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Nama file atau jalur file. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Contoh

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Mencoba mendeteksi enkoding file teks (TXT, TSV, CSV) dari aliran.

```python
def detect_encoding(cls, stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Contoh

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Lihat Juga
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
