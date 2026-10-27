---
title: "render_original_page_size 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "输出页面尺寸设置为匹配源 PDF 文档的页面尺寸。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

输出页面尺寸设置为匹配源 PDF 文档的页面尺寸。

默认情况下，GroupDocs.Viewer 会计算输出图像的页面大小以获得更好的渲染质量。启用此选项可确保输出页面的尺寸与源 PDF 文档的页面尺寸（以像素为单位）相同。默认值为 False。

此选项可用于渲染为 PNG 或 JPG 格式。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
