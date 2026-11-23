---
title: "proprietà is_search_term_reg_ex"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà che indica se il termine di ricerca deve essere trattato come espressione regolare o come letterale di testo."
type: docs
url: /it/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

La proprietà che indica se il termine di ricerca deve essere trattato come espressione regolare o come stringa letterale. Il valore predefinito è False — trattare come stringa letterale.

Se True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) è interpretato come un modello Regex .NET.

Se False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) è ricercato come un letterale di testo nel documento.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Vedi anche
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
