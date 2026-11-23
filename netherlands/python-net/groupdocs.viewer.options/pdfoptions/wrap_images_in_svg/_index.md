---
title: "eigenschap wrap_images_in_svg"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap die het omwikkelen van elke afbeelding in het uitvoer-HTML-document met een SVG-tag mogelijk maakt om de uitvoerkwaliteit te verbeteren."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

De eigenschap die het omwikkelen van elke afbeelding in het uitvoer-HTML-document met een SVG-tag mogelijk maakt om de uitvoerkwaliteit te verbeteren.

Standaard, bij het renderen van PDF‑ en Page Layout‑bestanden naar HTML, worden alle afbeeldingen gerenderd als één PNG‑afbeelding. De gerenderde PNG‑afbeelding wordt gebruikt als achtergrond voor het gegenereerde HTML‑document.

Deze optie is beschikbaar bij het renderen van PDF‑ en Page Layout‑bestandsformaten naar HTML met ingebedde en externe bronnen. Het maakt het mogelijk om elke afbeelding in het gegenereerde HTML‑document te omhullen met een SVG‑tag. De standaardwaarde is False.

Voor een codevoorbeeld, zie de documentatie.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Zie ook
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
