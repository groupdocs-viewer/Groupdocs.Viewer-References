---
title: "méthode detect_encoding"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Détecte l'encodage des fichiers texte TXT, TSV et CSV par chemin."
type: docs
url: /fr/python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 1010
---


## detect_encoding {#file_path}

Détecte l'encodage des fichiers texte TXT, TSV et CSV par chemin.

```python
def detect_encoding(cls, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le nom du fichier ou le chemin d'accès. |

**Returns:** str or None: The detected encoding name, or None when detection fails.

### Exemple

```python
from groupdocs.viewer import FileType

encoding = FileType.detect_encoding("message.txt")
if encoding:
    print(f"Detected encoding: {encoding}")
else:
    print("Failed to detect encoding.")
```

## detect_encoding {#stream}

Tente de détecter l'encodage des fichiers texte (TXT, TSV, CSV) à partir d'un flux.

```python
def detect_encoding(cls, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |

**Returns:** Encoding or None: The detected encoding, or None if detection fails.

### Exemple

```python
from groupdocs.viewer import FileType

with open("message.txt", "rb") as stream:
    encoding = FileType.detect_encoding(stream)
    print(encoding)
```

### Voir aussi
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
