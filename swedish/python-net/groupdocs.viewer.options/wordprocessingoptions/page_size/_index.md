---
title: "egenskapen page_size"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Storleken på utskriftssidan."
type: docs
url: /sv/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Storleken på utskriftssidan.

Standardvärdet är `PageSize.Unspecified`, vilket betyder att en sidstorlek som anges i sidinställningarna (Page Setup) används.

När HTM- och HTML-filer renderas är standardsidstorleken inställd på Letter 792 x 612 punkter.

Som ett resultat kan en del av innehållet inte få plats i sidramen.

Ange en större sidstorlek, t.ex. `PageSize.A3`, för att få plats med innehållet.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Se även
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
