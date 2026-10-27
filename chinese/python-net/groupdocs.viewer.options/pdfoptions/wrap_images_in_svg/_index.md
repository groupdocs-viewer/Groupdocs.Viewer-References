---
title: "wrap_images_in_svg 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

此属性可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。

默认情况下，将 PDF 和页面布局文件渲染为 HTML 时，所有图像会渲染为一个 PNG 图像。渲染后的 PNG 图像用作输出 HTML 文档的背景。

当将 PDF 和页面布局文件格式渲染为带有嵌入式和外部资源的 HTML 时，可使用此选项。它允许将输出 HTML 文档中的每个图像包装在 SVG 标签中。默认值为 False。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
