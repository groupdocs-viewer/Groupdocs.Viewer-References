---
title: "propriété remove_comments"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété désactive le rendu des commentaires lorsqu'elle est définie sur True."
type: docs
url: /fr/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

La propriété désactive le rendu des commentaires lorsqu’elle est définie sur True. Par défaut, elle est False, donc tous les commentaires sont affichés.

Certains formats de documents comme PDF et WordProcessing peuvent contenir des commentaires. Par défaut, GroupDocs.Viewer les rend. Avec cette option définie sur True, les commentaires peuvent être exclus du document résultant.

Cette option remplace la propriété obsolète `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Voir aussi
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
