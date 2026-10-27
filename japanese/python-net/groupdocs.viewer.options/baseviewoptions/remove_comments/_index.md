---
title: "remove_comments プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティを True に設定すると、コメントの描画が無効になります。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

このプロパティは True に設定された場合、コメントのレンダリングを無効にします。デフォルトは False で、すべてのコメントが表示されます。

PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれることがあります。デフォルトでは GroupDocs.Viewer がそれらを描画します。このオプションを True に設定すると、コメントが結果のドキュメントから除外される可能性があります。

このオプションは、廃止された `RenderComments` プロパティに置き換わります。

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### 参照
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
