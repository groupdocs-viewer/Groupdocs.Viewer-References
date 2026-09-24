---
title: disable_chars_grouping property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property disables symbol grouping for precise symbol positioning during page rendering."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

The property disables symbol grouping for precise symbol positioning during page rendering.

When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is False.

For code example, see the documentation.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### See Also
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
