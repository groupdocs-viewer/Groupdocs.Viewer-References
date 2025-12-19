---
title: disable_chars_grouping property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 30
---

## disable_chars_grouping property


Disables symbol grouping for precise symbol positioning during page rendering.

### Remarks 


When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is `false`. 




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-character-grouping).
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
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
