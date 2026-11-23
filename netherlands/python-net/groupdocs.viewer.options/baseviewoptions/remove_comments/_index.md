---
title: "eigenschap remove_comments"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De eigenschap schakelt het renderen van opmerkingen uit wanneer deze is ingesteld op True."
type: docs
url: /nl/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

De eigenschap schakelt het renderen van opmerkingen uit wanneer deze op True is ingesteld. Standaard is deze False, zodat alle opmerkingen worden weergegeven.

Sommige documentformaten zoals PDF en WordProcessing kunnen opmerkingen bevatten. Standaard rendert GroupDocs.Viewer deze. Met deze optie ingesteld op True kunnen de opmerkingen uit het resulterende document worden weggelaten.

Deze optie vervangt de verouderde `RenderComments` eigenschap.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Zie ook
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
