---
title: "render_header_footer_placeholders egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen möjliggör rendering av platshållare i sidhuvud och sidfot på en bild."
type: docs
url: /sv/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

Egenskapen möjliggör rendering av platshållare i sidhuvud och sidfot på en bild.

Den är inaktiverad som standard (`False`). Detta alternativ gäller för alla fyra renderingslägen för presentationer: HTML, PDF, PNG och JPEG. Det är inte tillämpligt när en presentation renderas till ren HTML/CSS-markup med hjälp av [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Se även
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
