---
title: "Свойство is_search_term_reg_ex"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство, указывающее, следует ли рассматривать поисковый термин как регулярное выражение или как текстовый литерал."
type: docs
url: /ru/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Свойство, указывающее, следует ли рассматривать поисковый запрос как регулярное выражение или как буквальный текст. По умолчанию False — рассматривать как буквальный текст.

Если True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) интерпретируется как шаблон .NET Regex.

Если False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) ищется как текстовый литерал в документе.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### См. также
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
