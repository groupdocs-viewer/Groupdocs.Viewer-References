---
title: "disable_copy_protection egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen inaktiverar skydd mot kopiering av innehåll när man renderar till HTML."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Egenskapen inaktiverar skydd mot kopiering av innehåll när man renderar till HTML.

När PDF‑filer renderas med skydd mot kopiering av text och bilder till HTML, lägger GroupDocs.Viewer till ett `inert`‑HTML‑attribut på HTML‑BODY‑taggen. Standardvärdet är `False`, vilket betyder att `inert`‑attributet endast läggs till om PDF‑dokumentet är skyddat.

För ett kodexempel, se dokumentationen.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Se även
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
