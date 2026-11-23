---
title: "exclude_fonts プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは HTML ドキュメントへのフォント追加を無効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/
is_root: false
weight: 2010
---


## exclude_fonts property

このプロパティは HTML ドキュメントへのフォント追加を無効にします。

既定では、GroupDocs.Viewer はドキュメントで使用されるフォントを HTML マークアップに埋め込みます。このプロパティは `False` の値です。フォントの埋め込みを防止するには、このプロパティを `True` に設定してください。

詳細とコード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def exclude_fonts(self):
    ...
@exclude_fonts.setter
def exclude_fonts(self, value):
    ...
```

### 参照
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
