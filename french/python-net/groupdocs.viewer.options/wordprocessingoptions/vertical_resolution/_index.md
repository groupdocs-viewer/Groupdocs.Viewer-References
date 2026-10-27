---
title: "propriété vertical_resolution"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La résolution verticale des images générées en points par pouce, utilisée uniquement lors du rendu des documents WordProcessing aux formats PNG ou JPEG."
type: docs
url: /fr/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/
is_root: false
weight: 2120
---


## vertical_resolution property

La résolution verticale des images générées en points par pouce, utilisée uniquement lors du rendu des documents WordProcessing aux formats PNG ou JPEG.

La valeur par défaut est de 96 DPI.

La valeur minimale possible est de 72 DPI et la valeur maximale possible est de 600 DPI. Si une valeur spécifiée par l'utilisateur est en dehors de ces limites, la borne la plus proche sera appliquée.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### Voir aussi
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
