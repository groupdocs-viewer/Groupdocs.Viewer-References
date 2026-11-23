---
title: "is_search_term_reg_ex eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap die aangeeft of de zoekterm moet worden behandeld als een reguliere expressie of als een tekstletterlijk."
type: docs
url: /nl/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

De eigenschap die aangeeft of de zoekterm moet worden behandeld als een reguliere expressie of als een letterlijke tekst. Standaard is False — behandelen als een letterlijke tekst.

Als True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) wordt geïnterpreteerd als een .NET Regex‑patroon.

Als False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) wordt gezocht als een tekstletterlijk in het document.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Zie ook
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
