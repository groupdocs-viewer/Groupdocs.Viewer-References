---
title: "propriété render_original_page_size"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La taille de page de sortie est définie pour correspondre à la taille de page du document PDF source."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

La taille de page de sortie est définie pour correspondre à la taille de page du document PDF source.

Par défaut, GroupDocs.Viewer calcule la taille de page de l'image de sortie pour une meilleure qualité de rendu. Activez cette option pour garantir que les pages de sortie ont la même taille que la taille de page du document PDF source (en pixels). La valeur par défaut est False.

Cette option est disponible pour le rendu aux formats PNG ou JPG.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
