---
title: "detect_encoding methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Detecteert de codering van tekst‑TXT, TSV‑ en CSV‑bestanden op basis van pad."
type: docs
url: /nl/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Detecteert de codering van tekst‑TXT, TSV‑ en CSV‑bestanden op basis van pad.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | De bestandsnaam of het bestandspad. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Voorbeeld

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Probeert de codering van tekstbestanden (TXT, TSV, CSV) uit een stream te detecteren.

```python
def detect_encoding(cls, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Voorbeeld

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Zie ook
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
