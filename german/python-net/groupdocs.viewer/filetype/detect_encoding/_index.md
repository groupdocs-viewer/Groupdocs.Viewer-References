---
title: "detect_encoding-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Ermittelt die Kodierung von Text‑TXT-, TSV‑ und CSV‑Dateien anhand des Pfads."
type: docs
url: /de/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Ermittelt die Kodierung von Text‑TXT-, TSV‑ und CSV‑Dateien anhand des Pfads.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateiname oder Dateipfad. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Beispiel

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Versucht, die Kodierung von Textdateien (TXT, TSV, CSV) aus einem Stream zu ermitteln.

```python
def detect_encoding(cls, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Beispiel

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Siehe auch
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
