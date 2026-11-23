---
title: "propriété fixed_layout"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "L'option de mise en page fixe active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

L'option de mise en page fixe active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe.

Les documents PDF et EPUB sont d'abord rendus en HTML avec une mise en page fixe afin de conserver l'apparence du document source. Cette mise en page fixe signifie que tous les éléments HTML ont des positions précises au sein d'un conteneur de taille définie. Redimensionner la fenêtre du navigateur n'affecte pas la position et la taille des éléments du document.

Cette option n'est disponible que lors du rendu en HTML. La valeur par défaut est `True`. Pour rendre avec une mise en page fluide, définissez cette propriété sur `False`.

Lors du rendu avec une mise en page fluide, les images sont ignorées. Utilisez la mise en page fluide lors du rendu de documents PDF contenant du texte.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
