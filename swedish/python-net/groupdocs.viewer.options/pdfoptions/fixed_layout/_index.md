---
title: "fixed_layout-egenskapen"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Alternativet för fast layout möjliggör rendering av PDF- och EPUB-dokument till HTML med en fast layout."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Alternativet för fast layout möjliggör rendering av PDF- och EPUB-dokument till HTML med en fast layout.

PDF- och EPUB-dokument renderas initialt till HTML med en fast layout för att bevara utseendet på källdokumentet. Denna fasta layout innebär att alla HTML-element har exakta positioner inom en behållare med en bestämd storlek. Att ändra storlek på webbläsarfönstret påverkar inte positionen och storleken på elementen i dokumentet.

Detta alternativ är endast tillgängligt vid rendering till HTML. Standardvärdet är `True`. För att rendera med en flytande layout, sätt denna egenskap till `False`.

När du renderar till fluid layout, hoppas bilder över. Använd fluid layout när du renderar PDF-dokument med textinnehåll.

För ett kodexempel, se dokumentationen.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Se även
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
