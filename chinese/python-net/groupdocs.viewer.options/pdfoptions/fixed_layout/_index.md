---
title: "fixed_layout 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "固定布局选项使 PDF 和 EPUB 文档以固定布局渲染为 HTML。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

固定布局选项使 PDF 和 EPUB 文档以固定布局渲染为 HTML。

PDF 和 EPUB 文档最初会以固定布局渲染为 HTML，以保持源文档的外观。该固定布局意味着所有 HTML 元素在具有固定尺寸的容器内具有精确的位置。调整浏览器窗口大小不会影响文档中元素的位置和大小。

此选项仅在渲染为 HTML 时可用。默认值为 `True`。若要使用流式布局渲染，请将此属性设置为 `False`。

在渲染为流式布局时，图像会被跳过。渲染包含文本内容的 PDF 文档时请使用流式布局。

有关代码示例，请参阅文档。

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### 另见
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
