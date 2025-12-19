---
title: fonts_to_exclude property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 110
---

## fonts_to_exclude property


The list of font names to exclude from HTML document.

### Remarks 


This option is supported for presentations only.




The fonts that are added into the HTML document improve stability of the output view, at the same time they increase the size of the rendering result. This option lets you balance between stability and output size. Include the font names that are popular and installed into most systems.




Please note, this property is active only when the [`HtmlViewOptions.exclude_fonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions#exclude_fonts) options is disabled.




For details and code example, see the [documentation](https://docs.groupdocs.com/viewer/net/exclude-fonts/).
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
* module [`groupdocs.viewer.options`](../../)
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions)
