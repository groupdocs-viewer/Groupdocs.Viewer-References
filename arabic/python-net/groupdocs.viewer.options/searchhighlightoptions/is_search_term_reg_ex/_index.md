---
title: "خاصية is_search_term_reg_ex"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية التي تشير إلى ما إذا كان يجب معاملة مصطلح البحث كتعبير نمطي أو كنص حرفي."
type: docs
url: /ar/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

الخاصية التي تشير إلى ما إذا كان يجب معالجة مصطلح البحث كتعبير نمطي أو كنص حرفي. القيمة الافتراضية هي False — معالجته كنص حرفي.

إذا كان True، فإن [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) يُفسَّر كنمط Regex في .NET.

إذا كان False، فإن [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) يُبحث كنص حرفي في المستند.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### انظر أيضًا
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
