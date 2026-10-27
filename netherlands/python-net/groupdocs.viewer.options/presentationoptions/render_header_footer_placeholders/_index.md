---
title: "render_header_footer_placeholders eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap maakt het renderen van tijdelijke aanduidingen in de kop‑ en voettekst van een dia mogelijk."
type: docs
url: /nl/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

De eigenschap maakt het renderen van tijdelijke aanduidingen in de kop‑ en voettekst van een dia mogelijk.

Deze is standaard uitgeschakeld (`False`). Deze optie is van toepassing op alle vier rendermodi van presentaties: HTML, PDF, PNG en JPEG. Hij is niet van toepassing bij het renderen van een presentatie naar pure HTML/CSS-markup met behulp van [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Zie ook
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
