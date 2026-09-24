---
title: render_header_footer_placeholders property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables rendering placeholders in header and footer of a slide."
type: docs
url: /python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

The property enables rendering placeholders in header and footer of a slide.

It is disabled by default (`False`). This option applies for all four rendering modes of presentations: HTML, PDF, PNG, and JPEG. It is not applicable when rendering a presentation to pure HTML/CSS markup using [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### See Also
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
