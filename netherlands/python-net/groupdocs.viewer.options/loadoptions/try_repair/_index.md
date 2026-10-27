---
title: "try_repair eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap stelt GroupDocs.Viewer in staat om te proberen structurele corruptie in PDF‑documenten te repareren."
type: docs
url: /nl/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

De eigenschap maakt het mogelijk voor GroupDocs.Viewer om te proberen structurele corruptie in PDF‑documenten te repareren. Standaard is False.

Deze functie behandelt de volgende problemen in een PDF-document:

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

### Zie ook
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
