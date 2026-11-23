---
title: "horizontal_resolution eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De horizontale resolutie voor gegenereerde afbeeldingen in dots per inch."
type: docs
url: /nl/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

De horizontale resolutie voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing-documenten naar PNG- of JPEG-formaten.

Standaardwaarde is 96 DPI. De minimale mogelijke waarde is 72 DPI; de maximale mogelijke waarde is 600 DPI. Als een door de gebruiker opgegeven waarde buiten deze limieten valt, wordt de dichtstbijzijnde grens (minimum of maximum) toegepast.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Zie ook
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
