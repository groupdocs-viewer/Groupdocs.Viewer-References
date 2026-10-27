---
title: "propriété remove_unused_objects"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété supprime les objets inutilisés (orphelins) d'un fichier PDF."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

La propriété supprime les objets inutilisés (orphelins) d'un fichier PDF.

Ces objets sont placés dans le document PDF mais ne sont référencés dans aucun dictionnaire de ressources de page et ne sont donc pas du tout utilisés. Activer cette propriété (`True`) réduira la taille du document PDF généré. Par défaut, elle est désactivée (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Voir aussi
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
