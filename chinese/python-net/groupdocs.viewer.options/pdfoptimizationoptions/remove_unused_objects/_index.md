---
title: "remove_unused_objects 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性移除 PDF 文件中未使用（孤立）的对象。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

该属性移除 PDF 文件中未使用（孤立）的对象。

这些对象已放置在 PDF 文档中，但未在任何页面的资源字典中被引用，因此根本未被使用。激活此属性 (`True`) 将减小输出 PDF 文档的大小。默认情况下它是禁用的 (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### 另见
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
