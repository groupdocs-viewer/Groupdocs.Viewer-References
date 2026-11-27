---
title: page_size property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The size of the output page; defaults to PageSize.Unspecified, which uses the page size defined in page settings."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

The size of the output page; defaults to `PageSize.Unspecified`, which uses the page size defined in page settings.

When rendering HTM and HTML files the default page size is Letter (792 × 612 points). As a result, some content may not fit into the page frame. Set a larger page size, e.g. `PageSize.A3`, to fit the contents.

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
