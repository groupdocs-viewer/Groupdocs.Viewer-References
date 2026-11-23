---
title: "enable_layered_rendering 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性在渲染为 HTML 时，按原始 PDF 文档的 Z 顺序渲染文本和图形。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

此属性在渲染为 HTML 时，按原始 PDF 文档的 Z 顺序渲染文本和图形。

默认情况下，GroupDocs.Viewer 将文本和图形渲染为 HTML 中的单个层。此选项允许您按照源文件中的顺序排列对象。默认值为 False。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
