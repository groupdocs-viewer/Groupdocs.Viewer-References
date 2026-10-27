---
title: "horizontal_resolution 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "生成图像的水平分辨率，以每英寸点数 (dpi) 为单位。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

生成图像的水平分辨率（每英寸点数）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。

默认值为 96 DPI。最小可能值为 72 DPI；最大可能值为 600 DPI。如果用户指定的值超出这些范围，将使用最近的边界值（最小或最大）。

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### 另见
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
