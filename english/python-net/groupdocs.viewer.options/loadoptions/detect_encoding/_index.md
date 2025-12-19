---
title: detect_encoding property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 30
---

## detect_encoding property


Enables the encoding detection for the [`FileType.TXT`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.CSV`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.TSV`](/viewer/python-net/groupdocs.viewer/filetype) files.

### Remarks 


If the encoding cannot be detected, the default [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions#encoding) is used. For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/detect-encoding-when-loading-documents/).
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
* module [`groupdocs.viewer.options`](../../)
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions)
