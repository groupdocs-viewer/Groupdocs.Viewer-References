---
title: "properti render_header_footer_placeholders"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini memungkinkan rendering placeholder di header dan footer slide."
type: docs
url: /id/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

Properti ini memungkinkan rendering placeholder di header dan footer slide.

Secara default, ini dinonaktifkan (`False`). Opsi ini berlaku untuk semua empat mode rendering presentasi: HTML, PDF, PNG, dan JPEG. Ini tidak berlaku saat merender presentasi ke markup HTML/CSS murni menggunakan [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### Lihat Juga
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
