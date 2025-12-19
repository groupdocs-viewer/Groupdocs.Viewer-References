---
title: page_size property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 60
---

## page_size property


The size of the output page.
The default value is [`PageSize.UNSPECIFIED`](/viewer/python-net/groupdocs.viewer.options/pagesize#UNSPECIFIED) which means that a page size is set in a page settings (Page Setup) is used.

When rendering HTM and HTML files the default page size is set to Letter 792 x 612 points.
As a result, some of the content may not fit into the page frame.
Set a larger page size e.g. [`PageSize.A3`](/viewer/python-net/groupdocs.viewer.options/pagesize#A3) to fit the contents.
### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PageSize`](/viewer/python-net/groupdocs.viewer.options/pagesize)
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions)
