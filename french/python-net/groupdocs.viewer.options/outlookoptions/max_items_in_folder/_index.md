---
title: "propriété max_items_in_folder"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Le nombre maximal de messages ou d'éléments pouvant être rendus depuis un dossier."
type: docs
url: /fr/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Le nombre maximal de messages ou d'éléments pouvant être rendus depuis un dossier.

Les fichiers de données Outlook peuvent être volumineux et la récupération de tous les messages peut prendre un temps considérable. Cette propriété limite le nombre maximal de messages ou d'éléments rendus. La valeur par défaut est `50`. Pour rendre tous les messages, définissez la valeur à `0`.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Voir aussi
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
