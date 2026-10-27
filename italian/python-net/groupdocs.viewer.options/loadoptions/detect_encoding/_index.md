---
title: "proprietà detect_encoding"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà consente il rilevamento della codifica per i file FileType.txt, FileType.csv e FileType.tsv."
type: docs
url: /it/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

La proprietà abilita il rilevamento della codifica per i file [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/) e [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/).

Se la codifica non può essere rilevata, viene utilizzata la predefinita [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/). Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### Vedi anche
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
