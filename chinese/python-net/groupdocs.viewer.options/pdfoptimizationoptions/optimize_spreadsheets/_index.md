---
title: "optimize_spreadsheets 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性启用对 PDF 文件中电子表格的优化。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/
is_root: false
weight: 2060
---


## optimize_spreadsheets property

该属性启用对 PDF 文件中电子表格的优化。

此优化通过设置边框线并移除代码为 32‑127 的 Arial 和 Times New Roman 字符来减小输出文件大小。默认值为 `False`。

代码示例请参阅 GroupDocs 文档。

### Definition:
```python
@property
def optimize_spreadsheets(self):
    ...
@optimize_spreadsheets.setter
def optimize_spreadsheets(self, value):
    ...
```

### 另见
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
