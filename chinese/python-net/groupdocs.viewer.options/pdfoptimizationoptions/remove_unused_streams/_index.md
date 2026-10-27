---
title: "remove_unused_streams 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性会移除 PDF 文件中未使用的（孤立的）流，这些流在页面资源字典中被引用但从未在页面内容中使用。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/
is_root: false
weight: 2100
---


## remove_unused_streams property

该属性移除 PDF 文件中未使用（孤立）的流，这些流在页面资源字典中被引用但在页面内容中从未使用。默认情况下已禁用（`False`）；将其设置为 `True` 可减小输出 PDF 的大小。

### Definition:
```python
@property
def remove_unused_streams(self):
    ...
@remove_unused_streams.setter
def remove_unused_streams(self, value):
    ...
```

### 另见
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
