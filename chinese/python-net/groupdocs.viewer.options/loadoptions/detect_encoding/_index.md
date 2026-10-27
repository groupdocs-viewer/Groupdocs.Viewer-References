---
title: "detect_encoding 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性启用对 FileType.txt、FileType.csv 和 FileType.tsv 文件的编码检测。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

该属性启用对 [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)、[`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)、以及 [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) 文件的编码检测。

如果无法检测到编码，将使用默认的 [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/)。有关代码示例，请参阅文档。

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### 另见
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
