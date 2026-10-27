---
title: "render_to_pure_html 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "此属性启用针对演示文稿文档的新 HTML 渲染模式——在此模式下，文件将渲染为纯 HTML/CSS 标记，不包含 SVG 图像。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/
is_root: false
weight: 2020
---


## render_to_pure_html property

该属性为演示文稿启用一种新的 HTML 渲染模式——在此模式下，文件渲染为纯 HTML/CSS 标记，不包含 SVG 图像。默认情况下此模式被禁用（`False`），使用现有的基于 SVG 的 HTML 渲染器。

代码示例请参阅位于 https://docs.groupdocs.com/viewer/net/render-presentations/#generate-pure-htmlcss-markup 的文档。

### Definition:
```python
@property
def render_to_pure_html(self):
    ...
@render_to_pure_html.setter
def render_to_pure_html(self, value):
    ...
```

### 另见
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
