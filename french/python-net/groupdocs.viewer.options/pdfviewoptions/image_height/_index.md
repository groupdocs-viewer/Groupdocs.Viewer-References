---
title: "Propriété image_height"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La hauteur d'une image de sortie en pixels."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

La hauteur d'une image de sortie en pixels.

Utilisez cette propriété pour définir la hauteur de l'image de sortie (en pixels). GroupDocs.Viewer applique cette propriété lors du rendu d'une seule image uniquement en HTML. Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

Si vous définissez cette propriété, la propriété [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) est ignorée.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Voir aussi
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
