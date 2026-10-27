---
title: "is_search_term_reg_ex プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "検索語が正規表現として扱われるかテキストリテラルとして扱われるかを示すプロパティです。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

このプロパティは、検索語句を正規表現として扱うかテキストリテラルとして扱うかを示します。デフォルトは False で、テキストリテラルとして扱います。

True の場合、[`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) は .NET の Regex パターンとして解釈されます。

False の場合、[`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) はドキュメント内でテキストリテラルとして検索されます。

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### 参照
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
