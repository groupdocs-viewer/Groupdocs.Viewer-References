---
title: "eigenschap disable_copy_protection"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap schakelt inhoudskopie-bescherming uit bij het renderen naar HTML."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

De eigenschap schakelt inhoudskopie-bescherming uit bij het renderen naar HTML.

Bij het renderen van PDF‑bestanden met bescherming tegen het kopiëren van tekst en afbeeldingen naar HTML, voegt GroupDocs.Viewer een `inert` HTML‑attribuut toe aan de HTML BODY‑tag. De standaardwaarde is `False`, wat betekent dat het `inert`‑attribuut alleen wordt toegevoegd als het PDF‑document beschermd is.

Voor een codevoorbeeld, zie de documentatie.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Zie ook
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
