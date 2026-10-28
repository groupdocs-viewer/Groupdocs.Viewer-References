---
title: "is_search_term_reg_ex özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Arama teriminin bir düzenli ifade olarak mı yoksa metin sabiti olarak mı ele alınacağını belirten özellik."
type: docs
url: /tr/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Arama teriminin düzenli ifade mi yoksa metin literalı mı olarak ele alınacağını belirten özellik. Varsayılan değer False — metin literalı olarak ele alın.

True ise, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) bir .NET Regex deseni olarak yorumlanır.

False ise, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) belgede metin sabiti olarak aranır.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Ayrıca Bakınız
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
