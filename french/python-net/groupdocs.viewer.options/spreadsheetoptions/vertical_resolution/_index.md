---
title: "propriété vertical_resolution"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La résolution verticale des images générées en points par pouce."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

La résolution verticale des images générées en points par pouce. Cette option n'est utilisée que lors du rendu des feuilles de calcul aux formats PNG ou JPEG.

La valeur par défaut est de 96 DPI. La valeur minimale possible est de 72 DPI ; la valeur maximale possible est de 600 DPI. Si une valeur spécifiée par l'utilisateur est hors de ces limites, la borne la plus proche sera appliquée.

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
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
