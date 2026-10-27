---
title: "disable_chars_grouping プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、ページレンダリング中の正確なシンボル配置のためにシンボルのグルーピングを無効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

このプロパティは、ページレンダリング中の正確なシンボル配置のためにシンボルのグルーピングを無効にします。

PDF ファイルを変換する際、GroupDocs.Viewer は個々の文字を単語にまとめてレンダリング性能を向上させます。文書に象形文字や特殊記号が含まれる場合、より正確なレイアウトを確保するために文字のグルーピングを禁止したいことがあります。デフォルト値は False です。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
