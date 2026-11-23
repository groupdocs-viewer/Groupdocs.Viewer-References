---
title: "render_header_footer_placeholders Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft ermöglicht das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie."
type: docs
url: /de/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

Die Eigenschaft ermöglicht das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie.

Sie ist standardmäßig deaktiviert (`False`). Diese Option gilt für alle vier Rendermodi von Präsentationen: HTML, PDF, PNG und JPEG. Sie ist nicht anwendbar, wenn eine Präsentation in reines HTML/CSS-Markup gerendert wird, indem [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/) verwendet wird.

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Siehe auch
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
