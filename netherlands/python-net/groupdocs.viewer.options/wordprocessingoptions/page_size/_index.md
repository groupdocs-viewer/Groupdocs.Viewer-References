---
title: "page_size eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De grootte van de uitvoerpagina."
type: docs
url: /nl/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

De grootte van de uitvoerpagina.

De standaardwaarde is `PageSize.Unspecified`, wat betekent dat een paginagrootte ingesteld in paginainstellingen (Pagina-instelling) wordt gebruikt.

Bij het renderen van HTM- en HTML-bestanden wordt de standaardpaginagrootte ingesteld op Letter 792 x 612 punten.

Als gevolg hiervan past een deel van de inhoud mogelijk niet in het paginarand.

Stel een grotere paginagrootte in, bijv. `PageSize.A3`, om de inhoud passend te maken.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Zie ook
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
