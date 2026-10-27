---
title: "is_search_term_reg_ex 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "指示搜索词应被视为正则表达式还是文本字面量的属性。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

此属性指示搜索词是应被视为正则表达式还是文本字面量。默认值为 False — 视为文本字面量。

如果为 True，[`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) 将被解释为 .NET 正则表达式模式。

如果为 False，[`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) 将作为文档中的文本字面量进行搜索。

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### 另见
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
