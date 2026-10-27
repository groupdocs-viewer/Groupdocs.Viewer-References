---
title: "metodo detect_encoding"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rileva la codifica dei file di testo TXT, TSV e CSV tramite percorso."
type: docs
url: /it/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Rileva la codifica dei file di testo TXT, TSV e CSV tramite percorso.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | `str` | Il nome del file o il percorso del file. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Esempio

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Tenta di rilevare la codifica dei file di testo (TXT, TSV, CSV) da uno stream.

```python
def detect_encoding(cls, stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Esempio

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Vedi anche
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
