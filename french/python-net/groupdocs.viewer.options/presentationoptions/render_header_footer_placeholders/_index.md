---
title: "propriété render_header_footer_placeholders"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété permet le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive."
type: docs
url: /fr/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

La propriété permet le rendu des espaces réservés dans l'en-tête et le pied de page d'une diapositive.

Elle est désactivée par défaut (`False`). Cette option s'applique aux quatre modes de rendu des présentations : HTML, PDF, PNG et JPEG. Elle n'est pas applicable lors du rendu d'une présentation en balisage HTML/CSS pur en utilisant [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Voir aussi
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
