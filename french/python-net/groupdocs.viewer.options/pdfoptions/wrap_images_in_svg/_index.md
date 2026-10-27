---
title: "propriété wrap_images_in_svg"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété qui active l'encapsulation de chaque image dans le document HTML de sortie dans une balise SVG pour améliorer la qualité de sortie."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

La propriété qui active l'encapsulation de chaque image dans le document HTML de sortie dans une balise SVG pour améliorer la qualité de sortie.

Par défaut, lors du rendu de fichiers PDF et de mise en page vers HTML, toutes les images sont rendues sous forme d'une seule image PNG. L'image PNG rendue est utilisée comme arrière-plan du document HTML de sortie.

Cette option est disponible lors du rendu des formats de fichiers PDF et de mise en page vers HTML avec des ressources intégrées et externes. Elle permet d'envelopper chaque image du document HTML de sortie dans une balise SVG. La valeur par défaut est False.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
