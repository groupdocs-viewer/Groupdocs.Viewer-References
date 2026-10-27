---
title: "propriété disable_copy_protection"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété désactive la protection contre la copie du contenu lors du rendu en HTML."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

La propriété désactive la protection contre la copie du contenu lors du rendu en HTML.

Lors du rendu de fichiers PDF avec protection contre la copie de texte et d'images vers HTML, GroupDocs.Viewer ajoute un attribut HTML `inert` à la balise HTML BODY. La valeur par défaut est `False`, ce qui signifie que l'attribut `inert` est ajouté uniquement si le document PDF est protégé.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
