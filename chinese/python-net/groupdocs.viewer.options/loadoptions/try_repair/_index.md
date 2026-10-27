---
title: "try_repair 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性使 GroupDocs.Viewer 能够尝试修复 PDF 文档中的结构损坏。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

该属性使 GroupDocs.Viewer 尝试修复 PDF 文档中的结构损坏。默认值为 False。

此功能解决 PDF 文档中的以下问题：

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### 另见
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
