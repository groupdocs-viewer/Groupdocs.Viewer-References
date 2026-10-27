---
title: "fonts_to_exclude プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "HTML ドキュメントから除外するフォント名のリストです。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

HTML ドキュメントから除外するフォント名のリストです。

HTMLドキュメントに追加されるフォントは出力ビューの安定性を向上させますが、同時にレンダリング結果のサイズが増加します。このオプションにより、安定性と出力サイズのバランスを取ることができます。一般的で多くのシステムにインストールされているフォント名を含めてください。

このプロパティは、[`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) オプションが無効な場合にのみ有効であることに注意してください。

詳細とコード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### 参照
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
