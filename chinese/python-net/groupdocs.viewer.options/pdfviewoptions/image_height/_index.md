---
title: "image_height 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "输出图像的高度（像素）。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

输出图像的高度（像素）。

使用此属性设置输出图像的高度（单位为像素）。GroupDocs.Viewer 在仅将单个图像渲染为 HTML 时会应用此属性。有关详细信息，请参阅位于 https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/ 的文档。

如果您设置此属性，则 [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) 属性将被忽略。

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### 另见
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
