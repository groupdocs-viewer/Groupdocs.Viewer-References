---
title: "fonts_to_exclude‑egenskapen"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Listan med typsnittsnamn som ska uteslutas från HTML-dokumentet."
type: docs
url: /sv/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

Listan med typsnittsnamn som ska uteslutas från HTML-dokumentet.

Typsnitten som läggs till i HTML‑dokumentet förbättrar stabiliteten i utsiktsvyn, men ökar samtidigt storleken på renderingsresultatet. Detta alternativ låter dig balansera mellan stabilitet och utskriftsstorlek. Inkludera de typsnittsnamn som är populära och installerade på de flesta system.

Observera att denna egenskap endast är aktiv när alternativet [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) är inaktiverat.

För detaljer och kodexempel, se dokumentationen.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Se även
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
