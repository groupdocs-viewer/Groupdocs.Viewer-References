---
title: "propiedad is_search_term_reg_ex"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad que indica si el término de búsqueda debe tratarse como una expresión regular o como un literal de texto."
type: docs
url: /es/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

La propiedad que indica si el término de búsqueda debe tratarse como una expresión regular o como un literal de texto. El valor predeterminado es False — tratar como un literal de texto.

Si es True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) se interpreta como un patrón Regex de .NET.

Si es False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) se busca como un literal de texto en el documento.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Ver también
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
