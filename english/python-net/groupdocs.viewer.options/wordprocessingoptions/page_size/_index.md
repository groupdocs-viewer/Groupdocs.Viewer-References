---
title: page_size property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The size of the output page."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

The size of the output page.

The default value is `PageSize.Unspecified`, which means that a page size set in page settings (Page Setup) is used.

When rendering HTM and HTML files the default page size is set to Letter 792 x 612 points.

As a result, some of the content may not fit into the page frame.

Set a larger page size e.g. `PageSize.A3` to fit the contents.

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
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
