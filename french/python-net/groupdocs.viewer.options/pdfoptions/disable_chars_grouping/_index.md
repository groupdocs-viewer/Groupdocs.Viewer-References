---
title: "propriété disable_chars_grouping"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

La propriété désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page.

Lors de la conversion de fichiers PDF, GroupDocs.Viewer regroupe les caractères individuels en mots pour améliorer les performances de rendu. Si votre document contient des hiéroglyphes ou des symboles spéciaux, vous pouvez souhaiter interdire le regroupement des caractères afin d'assurer une mise en page plus précise. La valeur par défaut est False.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
