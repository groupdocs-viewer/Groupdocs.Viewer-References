---
title: "try_repair Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft ermöglicht es GroupDocs.Viewer, zu versuchen, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren."
type: docs
url: /de/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Die Eigenschaft ermöglicht es GroupDocs.Viewer, zu versuchen, strukturelle Beschädigungen in PDF-Dokumenten zu reparieren. Der Standardwert ist False.

Diese Funktion behebt die folgenden Probleme in einem PDF-Dokument:

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

### Siehe auch
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
