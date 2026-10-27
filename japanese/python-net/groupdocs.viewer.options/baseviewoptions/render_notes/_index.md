---
title: "render_notes プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、一部の形式に対してノートと注釈のレンダリングを有効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

このプロパティは、一部の形式に対してノートと注釈のレンダリングを有効にします。

プレゼンテーションや Microsoft Project ファイルなどの一部の形式にはノートが含まれることがあります。また、PDF ファイルにはデフォルトで非表示となり、マウスカーソルを合わせたときに PDF ビューアでのみ表示されるポップアップ注釈（バルーンヒント）がある場合があります。デフォルトでは、GroupDocs.Viewer はそのようなノートや注釈を描画しません（`False`）。これを有効にするには、このプロパティを `True` に設定してください。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### 参照
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
