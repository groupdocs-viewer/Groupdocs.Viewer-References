---
title: "detect_encoding Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft ermöglicht die Erkennung der Kodierung für Dateien vom Typ FileType.txt, FileType.csv und FileType.tsv."
type: docs
url: /de/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

Die Eigenschaft aktiviert die Erkennung der Kodierung für [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), und [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) Dateien.

Wenn die Kodierung nicht erkannt werden kann, wird die Standard‑[`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) verwendet. Ein Codebeispiel finden Sie in der Dokumentation.

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### Siehe auch
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
