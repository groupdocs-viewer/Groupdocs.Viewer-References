---
title: max_items property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The maximum number of messages or items to render."
type: docs
url: /python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 2020
---


## max_items property

The maximum number of messages or items to render.

Mail storage data files can be large and retrieving all messages can take significant time. This property limits the maximum number of messages or items that are rendered. Default value is 0 – all messages are rendered.

For a code example, see the documentation.

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
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions/)
