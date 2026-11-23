---
title: "render_text_as_image 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此选项可在 HTML 输出中将 PDF 文件中的文本渲染为图像。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

此选项可在 HTML 输出中将 PDF 文件中的文本渲染为图像。

当此选项设置为 True 时，GroupDocs.Viewer 会在 HTML 输出中将文本渲染为图像。这使得文本不可选择，并增强字符渲染，确保在 HTML 中呈现类似 PDF 的外观。默认值为 False。

此选项适用于渲染为 HTML。

代码示例请参见文档。

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
