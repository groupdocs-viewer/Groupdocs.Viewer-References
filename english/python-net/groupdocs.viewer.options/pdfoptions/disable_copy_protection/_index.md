---
title: disable_copy_protection property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 40
---

## disable_copy_protection property


Turns off content copy protection when rendering to HTML.

### Remarks 


When rendering PDF files with protection against copying text and images to HTML, GroupDocs.Viewer adds an 'inert' HTML attribute to the HTML BODY tag. The default value of this option is `false`, indicating that the 'intent' HTML attribute is added only if the PDF document is protected.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).
### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
