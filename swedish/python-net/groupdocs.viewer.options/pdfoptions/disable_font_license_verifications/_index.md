---
title: "disable_font_license_verifications egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen inaktiverar alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Egenskapen inaktiverar alla licensrestriktioner för alla teckensnitt i det aktuella XPS/OXPS-dokumentet.

Många operationer med teckensnitt kan inte utföras om de är förbjudna av teckensnittets licens. Till exempel kan vissa teckensnitt inte bäddas in i ett PDF‑dokument om licensreglerna förbjuder inbäddning för det teckensnittet. Detta alternativ låter dig hoppa över verifiering av dessa regler.

Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens‑ eller lagöverträdelser. Det rekommenderas starkt att endast använda flaggan när du är helt säker på att du inte bryter mot upphovsrättslagen. Standardvärdet är `False`.

För ett kodexempel, se dokumentationen på https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Se även
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
