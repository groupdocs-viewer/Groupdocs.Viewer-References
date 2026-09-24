---
title: remove_comments property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property disables rendering comments when set to True."
type: docs
url: /python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

The property disables rendering comments when set to True. By default it is False, so all comments are displayed.

Some document formats like PDF and WordProcessing may contain comments. By default the GroupDocs.Viewer renders them. With this option set to True the comments may be excluded from the resultant document.

This option replaces the obsolete `RenderComments` property.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### See Also
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
