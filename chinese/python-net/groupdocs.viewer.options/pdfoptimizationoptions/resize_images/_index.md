---
title: "resize_images 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性可设置输出 PDF 文件的最大分辨率。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/
is_root: false
weight: 2110
---


## resize_images property

此属性可设置输出 PDF 文件的最大分辨率。

要启用此选项，请将 [`PdfOptimizationOptions.compress_images`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) 属性设置为 `True`。此选项允许设置 [`PdfOptimizationOptions.max_resolution`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) 属性。

### Definition:
```python
@property
def resize_images(self):
    ...
@resize_images.setter
def resize_images(self, value):
    ...
```

### 另见
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
