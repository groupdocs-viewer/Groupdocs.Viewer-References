---
title: render_notes property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables rendering notes and annotations for some formats."
type: docs
url: /python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

The property enables rendering notes and annotations for some formats.

Some formats, such as presentations or Microsoft project files, may contain notes. Also, PDF files may have popup annotations (balloon hints) that are hidden by default and are visible in a PDF viewer only when pointing the mouse cursor on them. By default, GroupDocs.Viewer does not render such notes and annotations (`False`). To do this, set this property to `True`.

For a code example, see the documentation.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### See Also
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
