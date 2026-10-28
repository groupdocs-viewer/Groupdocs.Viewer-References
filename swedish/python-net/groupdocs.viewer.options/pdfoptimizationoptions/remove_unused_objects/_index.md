---
title: "remove_unused_objects egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen tar bort oanvända (föräldralösa) objekt från en PDF-fil."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

Egenskapen tar bort oanvända (föräldralösa) objekt från en PDF-fil.

Dessa objekt placeras i PDF-dokumentet men refereras inte från resursdictionaryn för någon sida och används därför inte alls. Att aktivera denna egenskap (`True`) minskar storleken på den genererade PDF-dokumentet. Som standard är den inaktiverad (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Se även
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
