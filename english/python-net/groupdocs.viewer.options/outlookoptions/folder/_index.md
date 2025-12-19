---
title: folder property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/outlookoptions/folder/
is_root: false
weight: 40
---

## folder property


Sets the name of the folder (e.g. Inbox, Sent Item or Deleted Items) to render.

### Remarks 


When rendering an Outlook data file, GroupDocs.Viewer renders messages from all folders contained in the file (including nested folders). Use this property  to render items from a specific folder.




For code example, see this [documentation](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#render-a-specific-folder).
### Definition:
```python
@property
def folder(self):
    ...
@folder.setter
def folder(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions)
