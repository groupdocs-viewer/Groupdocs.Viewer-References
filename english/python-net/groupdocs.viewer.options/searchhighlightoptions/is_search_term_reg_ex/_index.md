---
title: is_search_term_reg_ex property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property indicating whether the search term should be treated as a regular expression or as a text literal."
type: docs
url: /python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

The property indicating whether the search term should be treated as a regular expression or as a text literal. Default is False — treat as a text literal.

If True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) is interpreted as a .NET Regex pattern.

If False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) is searched as a text literal in the document.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### See Also
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
