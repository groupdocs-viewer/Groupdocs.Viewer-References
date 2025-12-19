---
title: unlink_table_of_contents property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/
is_root: false
weight: 100
---

## unlink_table_of_contents property


When rendering to HTML or PDF, you can set this option to `true` to disable navigation from the table of contents.
For HTML rendering, `a` tags with relative links will be replaced with `span` tags, removing functionality but preserving visual appearance.
For PDF rendering, the table of contents will be rendered as plain text without links to document sections.

### Remarks 


Default value is `false`.
### Definition:
```python
@property
def unlink_table_of_contents(self):
    ...
@unlink_table_of_contents.setter
def unlink_table_of_contents(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions)
