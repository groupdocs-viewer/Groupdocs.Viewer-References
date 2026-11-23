---
title: "propriété horizontal_resolution"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La résolution horizontale des images générées en points par pouce."
type: docs
url: /fr/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

La résolution horizontale des images générées en points par pouce. Cette option est utilisée uniquement lors du rendu des documents WordProcessing au format PNG ou JPEG.

La valeur par défaut est de 96 DPI. La valeur minimale possible est de 72 DPI ; la valeur maximale possible est de 600 DPI. Si une valeur spécifiée par l'utilisateur est en dehors de ces limites, la borne la plus proche (minimum ou maximum) sera appliquée.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Voir aussi
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
