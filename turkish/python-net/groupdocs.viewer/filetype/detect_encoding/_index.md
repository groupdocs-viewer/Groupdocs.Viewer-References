---
title: "detect_encoding yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Metin TXT, TSV ve CSV dosyalarının kodlamasını yol üzerinden algılar."
type: docs
url: /tr/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Metin TXT, TSV ve CSV dosyalarının kodlamasını yol üzerinden algılar.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Dosya adı veya dosya yolu. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Örnek

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Metin dosyalarının (TXT, TSV, CSV) kodlamasını bir akıştan algılamaya çalışır.

```python
def detect_encoding(cls, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Örnek

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Ayrıca Bakınız
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
