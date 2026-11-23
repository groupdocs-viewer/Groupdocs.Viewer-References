---
title: "propriété page_size"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La taille de la page de sortie."
type: docs
url: /fr/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

La taille de la page de sortie.

La valeur par défaut est `PageSize.Unspecified`, ce qui signifie qu'une taille de page définie dans les paramètres de page (Mise en page) est utilisée.

Lors du rendu des fichiers HTM et HTML, la taille de page par défaut est définie sur Letter 792 x 612 points.

En conséquence, une partie du contenu peut ne pas tenir dans le cadre de la page.

Définissez une taille de page plus grande, par ex. `PageSize.A3`, pour faire tenir le contenu.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Voir aussi
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
