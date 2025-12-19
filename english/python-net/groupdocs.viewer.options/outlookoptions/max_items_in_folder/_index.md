---
title: max_items_in_folder property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 50
---

## max_items_in_folder property


The maximum number of messages or items, that can be rendered from one folder.

### Remarks 


Outlook data files can be large and retrieving all messages can take significant time. This property limits the maximum number of messages or items that are rendered. Default value is `50`. To render all messages, set the value to `0`.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).
### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions)
