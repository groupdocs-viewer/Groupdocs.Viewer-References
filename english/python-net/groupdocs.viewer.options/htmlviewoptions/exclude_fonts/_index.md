---
title: exclude_fonts property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property disables adding any fonts into the HTML document."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/
is_root: false
weight: 2010
---


## exclude_fonts property

The property disables adding any fonts into the HTML document.

By default, GroupDocs.Viewer embeds the fonts used in the document into the HTML markup, and this property has a `False` value. To prevent embedding fonts, set this property to `True`.

For details and a code example, see the documentation.

### Definition:
```python
@property
def exclude_fonts(self):
    ...
@exclude_fonts.setter
def exclude_fonts(self, value):
    ...
```

### See Also
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
