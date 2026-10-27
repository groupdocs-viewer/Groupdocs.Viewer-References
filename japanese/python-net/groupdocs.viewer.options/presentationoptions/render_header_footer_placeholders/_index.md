---
title: "render_header_footer_placeholders プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティはスライドのヘッダーとフッターにプレースホルダーの描画を有効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

このプロパティはスライドのヘッダーとフッターにプレースホルダーの描画を有効にします。

デフォルトでは無効 (`False`) です。このオプションはプレゼンテーションの 4 つのレンダリングモード（HTML、PDF、PNG、JPEG）すべてに適用されます。[`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/) を使用してプレゼンテーションを純粋な HTML/CSS マークアップにレンダリングする場合は適用されません。

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### 参照
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
