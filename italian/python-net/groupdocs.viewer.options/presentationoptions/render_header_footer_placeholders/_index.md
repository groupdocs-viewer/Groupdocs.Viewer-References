---
title: "proprietà render_header_footer_placeholders"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà consente il rendering dei segnaposto nell'intestazione e nel piè di pagina di una diapositiva."
type: docs
url: /it/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

La proprietà consente il rendering dei segnaposto nell'intestazione e nel piè di pagina di una diapositiva.

È disabilitata per impostazione predefinita (`False`). Questa opzione si applica a tutte e quattro le modalità di rendering delle presentazioni: HTML, PDF, PNG e JPEG. Non è applicabile quando si renderizza una presentazione in markup HTML/CSS puro utilizzando [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Vedi anche
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
