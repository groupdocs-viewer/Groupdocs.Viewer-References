---
title: "render_header_footer_placeholders 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "该属性启用在幻灯片的页眉和页脚中渲染占位符。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

该属性启用在幻灯片的页眉和页脚中渲染占位符。

默认情况下它是禁用的（`False`）。此选项适用于演示文稿的所有四种渲染模式：HTML、PDF、PNG 和 JPEG。当使用 [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/) 将演示文稿渲染为纯 HTML/CSS 标记时，此选项不适用。

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### 另见
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
