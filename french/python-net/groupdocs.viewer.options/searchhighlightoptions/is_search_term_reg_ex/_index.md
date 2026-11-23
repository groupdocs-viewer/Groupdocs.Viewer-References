---
title: "propriété is_search_term_reg_ex"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété indiquant si le terme de recherche doit être traité comme une expression régulière ou comme un texte littéral."
type: docs
url: /fr/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

La propriété indiquant si le terme de recherche doit être traité comme une expression régulière ou comme un texte littéral. La valeur par défaut est False — traiter comme un texte littéral.

Si True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) est interprété comme un modèle Regex .NET.

Si False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) est recherché comme un texte littéral dans le document.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Voir aussi
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
