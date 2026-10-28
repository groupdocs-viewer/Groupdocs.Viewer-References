---
title: "método detect_encoding"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Detecta la codificación de archivos de texto TXT, TSV y CSV por ruta."
type: docs
url: /es/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Detecta la codificación de archivos de texto TXT, TSV y CSV por ruta.

```python
def detect_encoding(cls, file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | `str` | El nombre del archivo o la ruta del archivo. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Ejemplo

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Intenta detectar la codificación de archivos de texto (TXT, TSV, CSV) desde un flujo.

```python
def detect_encoding(cls, stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Ejemplo

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Ver también
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
