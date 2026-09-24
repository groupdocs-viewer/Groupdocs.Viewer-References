---
title: fonts_to_exclude property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The list of font names to exclude from HTML document."
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

The list of font names to exclude from HTML document.

The fonts that are added into the HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option lets you balance between stability and output size. Include the font names that are popular and installed into most systems.

Please note, this property is active only when the [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) options is disabled.

For details and code example, see the documentation.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### See Also
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
