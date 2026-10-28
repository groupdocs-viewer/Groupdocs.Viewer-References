---
title: "remove_comments egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Egenskapen inaktiverar rendering av kommentarer när den är satt till True."
type: docs
url: /sv/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Egenskapen inaktiverar rendering av kommentarer när den är satt till True. Som standard är den False, så alla kommentarer visas.

Vissa dokumentformat som PDF och WordProcessing kan innehålla kommentarer. Som standard renderar GroupDocs.Viewer dem. Med detta alternativ satt till True kan kommentarer uteslutas från det resulterande dokumentet.

Detta alternativ ersätter den föråldrade `RenderComments` egenskapen.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Se även
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
