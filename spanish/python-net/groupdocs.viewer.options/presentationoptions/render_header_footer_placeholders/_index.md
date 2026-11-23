---
title: "propiedad render_header_footer_placeholders"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad permite la representación de marcadores de posición en el encabezado y pie de diapositiva."
type: docs
url: /es/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

La propiedad permite la representación de marcadores de posición en el encabezado y pie de diapositiva.

Está deshabilitado por defecto (`False`). Esta opción se aplica a los cuatro modos de renderizado de presentaciones: HTML, PDF, PNG y JPEG. No es aplicable al renderizar una presentación a marcado HTML/CSS puro usando [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Ver también
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
