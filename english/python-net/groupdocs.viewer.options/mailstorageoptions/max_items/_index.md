---
title: max_items property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 40
---

## max_items property


Sets the maximum number of messages or items to render.

### Remarks 


Mail storage data files can be large and retrieving all messages can take significant time. This property limits the maximum number of messages or items that are rendered. Default value is 0 - all messages are rendered.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).
### Definition:
```python
@property
def max_items(self):
    ...
@max_items.setter
def max_items(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions)
