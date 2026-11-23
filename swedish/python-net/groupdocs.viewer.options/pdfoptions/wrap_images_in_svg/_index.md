---
title: "wrap_images_in_svg egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen som möjliggör att omsluta varje bild i HTML-utdatafilen i en SVG-tagg för att förbättra utdata kvaliteten."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Egenskapen som möjliggör att omsluta varje bild i HTML-utdatafilen i en SVG-tagg för att förbättra utdata kvaliteten.

Som standard, när PDF‑ och Page Layout‑filer renderas till HTML, renderas alla bilder som en enda PNG‑bild. Den renderade PNG‑bilden används som bakgrund för det resulterande HTML‑dokumentet.

Detta alternativ är tillgängligt när PDF‑ och Page Layout‑filformat renderas till HTML med inbäddade och externa resurser. Det möjliggör att omsluta varje bild i det resulterande HTML‑dokumentet i en SVG‑tagg. Standardvärdet är False.

För ett kodexempel, se dokumentationen.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Se även
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
