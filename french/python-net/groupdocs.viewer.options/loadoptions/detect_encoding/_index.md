---
title: "propriété detect_encoding"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété permet la détection de l'encodage pour les fichiers FileType.txt, FileType.csv et FileType.tsv."
type: docs
url: /fr/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

La propriété active la détection d’encodage pour les fichiers [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), et [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/).

Si l'encodage ne peut pas être détecté, la valeur par défaut [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) est utilisée. Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### Voir aussi
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
