---
title: disable_copy_protection property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property disables content copy protection when rendering to HTML."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

The property disables content copy protection when rendering to HTML.

When rendering PDF files with protection against copying text and images to HTML, GroupDocs.Viewer adds an `inert` HTML attribute to the HTML BODY tag. The default value is `False`, meaning the `inert` attribute is added only if the PDF document is protected.

For a code example, see the documentation.

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
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
