---
title: "ιδιότητα is_search_term_reg_ex"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα που υποδεικνύει εάν ο όρος αναζήτησης πρέπει να αντιμετωπίζεται ως κανονική έκφραση ή ως κυριολεκτικό κείμενο."
type: docs
url: /el/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

Η ιδιότητα που υποδεικνύει εάν ο όρος αναζήτησης πρέπει να αντιμετωπίζεται ως κανονική έκφραση ή ως κυριολεκτικό κείμενο. Η προεπιλογή είναι False — αντιμετωπίστε το ως κυριολεκτικό κείμενο.

Εάν True, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) ερμηνεύεται ως μοτίβο .NET Regex.

Εάν False, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/) αναζητείται ως κυριολεκτικό κείμενο στο έγγραφο.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### Δείτε επίσης
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
