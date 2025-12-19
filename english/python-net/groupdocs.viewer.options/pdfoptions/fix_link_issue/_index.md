---
title: fix_link_issue property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/fix_link_issue/
is_root: false
weight: 80
---

## fix_link_issue property


Tries to fix the issue when whole HTML page content is a link. Works only when input format is PDF and output format is HTML (with embedded or external resources). By default is disabled (`false`). Turn it on only when you know what and why you're doing. Turing this option on increases the document processing time.
### Definition:
```python
@property
def fix_link_issue(self):
    ...
@fix_link_issue.setter
def fix_link_issue(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
