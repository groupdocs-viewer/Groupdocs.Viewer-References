---
title: "remove_unused_objects eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap verwijdert ongebruikte (verweesde) objecten uit een PDF‑bestand."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

De eigenschap verwijdert ongebruikte (verweesde) objecten uit een PDF‑bestand.

Deze objecten worden in het PDF-document geplaatst, maar worden niet gerefereerd vanuit de resource‑woordenboeken van enige pagina en worden daardoor helemaal niet gebruikt. Het activeren van deze eigenschap (`True`) zal de grootte van het gegenereerde PDF‑document verkleinen. Standaard is deze uitgeschakeld (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Zie ook
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
