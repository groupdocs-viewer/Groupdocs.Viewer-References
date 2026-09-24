---
title: detect_encoding property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables encoding detection for FileType.txt, FileType.csv, and FileType.tsv files."
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

The property enables encoding detection for [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), and [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) files.

If the encoding cannot be detected, the default [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) is used. For a code example, see the documentation.

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### See Also
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
