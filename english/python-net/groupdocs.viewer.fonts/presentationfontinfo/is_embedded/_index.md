---
title: is_embedded property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property indicates whether the font is embedded inside the document and loaded into the Viewer instance (True), or is a system font (False)."
type: docs
url: /python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

The property indicates whether the font is embedded inside the document and loaded into the [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instance (`True`), or is a system font (`False`).

Spreadsheet documents cannot hold embedded fonts, so this property always returns `False` for them.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### See Also
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
