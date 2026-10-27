---
title: "propriété is_embedded"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété indique si la police est incorporée dans le document et chargée dans l'instance du Viewer (True), ou si c'est une police système (False)."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

La propriété indique si la police est incorporée dans le document et chargée dans l'instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), ou s'il s'agit d'une police système (`False`).

Les documents de feuille de calcul ne peuvent pas contenir de polices incorporées, ainsi cette propriété renvoie toujours `False` pour eux.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### Voir aussi
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
