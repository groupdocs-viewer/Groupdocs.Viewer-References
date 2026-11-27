---
title: fix_thai_marks property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The option to fix stranded Thai marks when rendering PDF to HTML."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/fix_thai_marks/
is_root: false
weight: 2060
---


## fix_thai_marks property

The option to fix stranded Thai marks when rendering PDF to HTML. Disabled by default (`False`); when enabled, applies a special Thai glyphs analyzer to correct issues, which may significantly degrade performance.

This option is applicable only when rendering input PDF to output HTML with embedded resources only; HTML with external resources are not supported yet.

### Definition:
```python
@property
def fix_thai_marks(self):
    ...
@fix_thai_marks.setter
def fix_thai_marks(self, value):
    ...
```

### See Also
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
