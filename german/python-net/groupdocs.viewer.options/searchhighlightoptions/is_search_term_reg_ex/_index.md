---
title: "is_search_term_reg_ex Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft, die angibt, ob der Suchbegriff als regulärer Ausdruck oder als Textliteral behandelt werden soll."
type: docs
url: /de/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Die Eigenschaft gibt an, ob der Suchbegriff als regulärer Ausdruck oder als Textliteral behandelt werden soll. Standard ist False — als Textliteral behandeln.

Wenn True, wird [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) als .NET‑Regex‑Muster interpretiert.

Wenn False, wird [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) im Dokument als Textliteral gesucht.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Siehe auch
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
