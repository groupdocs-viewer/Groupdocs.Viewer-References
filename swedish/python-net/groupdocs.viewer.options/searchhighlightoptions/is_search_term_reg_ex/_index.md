---
title: "is_search_term_reg_ex egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen som indikerar om sökordet ska behandlas som ett reguljärt uttryck eller som en textsträng."
type: docs
url: /sv/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Egenskapen som anger om sökordet ska behandlas som ett reguljärt uttryck eller som en textsträng. Standard är False — behandla som en textsträng.

Om True, tolkas [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) som ett .NET Regex‑mönster.

Om False, söks [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) som en textsträng i dokumentet.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Se även
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
