---
title: "fixed_layout eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De optie vaste lay-out maakt het renderen van PDF- en EPUB-documenten naar HTML met een vaste lay-out mogelijk."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

De optie vaste lay-out maakt het renderen van PDF- en EPUB-documenten naar HTML met een vaste lay-out mogelijk.

PDF‑ en EPUB‑documenten worden aanvankelijk gerenderd naar HTML met een vaste lay‑out om het uiterlijk van het bron‑document te behouden. Deze vaste lay‑out betekent dat alle HTML‑elementen precieze posities hebben binnen een container met een vaste grootte. Het wijzigen van de grootte van het browservenster heeft geen invloed op de positie en grootte van de elementen in het document.

Deze optie is alleen beschikbaar bij het renderen naar HTML. De standaardwaarde is `True`. Om te renderen met een vloeiende lay‑out, stel deze eigenschap in op `False`.

Bij het renderen met een vloeiende lay‑out worden afbeeldingen overgeslagen. Gebruik een vloeiende lay‑out bij het renderen van PDF‑documenten met tekstinhoud.

Voor een codevoorbeeld, zie de documentatie.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Zie ook
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
