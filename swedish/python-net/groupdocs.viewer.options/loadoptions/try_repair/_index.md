---
title: "try_repair-egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen gör det möjligt för GroupDocs.Viewer att försöka reparera strukturell korruption i PDF-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Egenskapen möjliggör för GroupDocs.Viewer att försöka reparera strukturell korruption i PDF-dokument. Standard är False.

Denna funktion hanterar följande problem i ett PDF-dokument:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### Se även
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
