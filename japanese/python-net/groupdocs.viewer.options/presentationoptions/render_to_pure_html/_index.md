---
title: "render_to_pure_html プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは Presentation ドキュメント用の新しい HTML レンダリングモードを有効にします。このモードでは、ファイルが SVG 画像なしで純粋な HTML/CSS マークアップとしてレンダリングされます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/
is_root: false
weight: 2020
---


## render_to_pure_html property

このプロパティはプレゼンテーション ドキュメント用の新しい HTML 描画モードを有効にします。このモードではファイルが SVG 画像なしの純粋な HTML/CSS マークアップに描画されます。デフォルトでは無効 (`False`) で、既存の SVG ベースの HTML レンダラーが使用されます。

コードサンプルについては、https://docs.groupdocs.com/viewer/net/render-presentations/#generate-pure-htmlcss-markup のドキュメントをご覧ください。

### Definition:
```python
@property
def render_to_pure_html(self):
    ...
@render_to_pure_html.setter
def render_to_pure_html(self, value):
    ...
```

### 参照
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
