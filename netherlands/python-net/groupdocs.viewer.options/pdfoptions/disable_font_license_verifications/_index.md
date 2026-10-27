---
title: "eigenschap disable_font_license_verifications"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap schakelt alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

De eigenschap schakelt alle licentiebeperkingen voor alle lettertypen in het huidige XPS/OXPS-document uit.

Veel bewerkingen met lettertypen kunnen niet worden uitgevoerd als ze verboden zijn door de licentie van het lettertype. Bijvoorbeeld, sommige lettertypen kunnen niet in een PDF‑document worden ingesloten als licentieregels het insluiten voor dat lettertype uitschakelen. Deze optie stelt u in staat om de verificatie van deze regels over te slaan.

Wees voorzichtig bij het gebruik van deze vlag. Wanneer deze is ingesteld, betekent dit dat de persoon die deze vlag instelt alle verantwoordelijkheid draagt voor mogelijke licentie- of wettelijke overtredingen. Het wordt sterk aanbevolen deze vlag alleen te gebruiken wanneer u er volledig van overtuigd bent dat u geen auteursrechtwetgeving overtreedt. De standaardwaarde is `False`.

Voor een codevoorbeeld, zie de documentatie op https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Zie ook
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
