---
title: "properti is_search_term_reg_ex"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti yang menunjukkan apakah istilah pencarian harus diperlakukan sebagai ekspresi reguler atau sebagai literal teks."
type: docs
url: /id/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Properti yang menunjukkan apakah istilah pencarian harus diperlakukan sebagai ekspresi reguler atau sebagai literal teks. Defaultnya False — perlakukan sebagai literal teks.

Jika True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) diinterpretasikan sebagai pola Regex .NET.

Jika False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) dicari sebagai literal teks dalam dokumen.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Lihat Juga
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
