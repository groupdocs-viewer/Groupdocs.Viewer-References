---
title: "image_width 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "输出图像的宽度（像素）。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/
is_root: false
weight: 2040
---


## image_width property

输出图像的宽度（像素）。

使用此属性设置输出图像的宽度（单位为像素）。GroupDocs.Viewer 在将单个图像渲染为 PDF 时会应用此属性。有关详细信息，请参阅文档。

如果您设置此属性，则 [`PdfViewOptions.ImageMaxWidth`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) 属性将被忽略。

### Definition:
```python
@property
def image_width(self):
    ...
@image_width.setter
def image_width(self, value):
    ...
```

### 另见
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
