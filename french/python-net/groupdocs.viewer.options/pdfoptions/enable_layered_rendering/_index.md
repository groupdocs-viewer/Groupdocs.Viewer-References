---
title: "propriété enable_layered_rendering"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété active le rendu du texte et des graphiques dans l'ordre Z du document PDF original lors du rendu en HTML."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

La propriété active le rendu du texte et des graphiques dans l'ordre Z du document PDF original lors du rendu en HTML.

Par défaut, GroupDocs.Viewer rend le texte et les graphiques comme une seule couche en HTML. Cette option vous permet d'organiser les objets dans le même ordre que dans le fichier source. La valeur par défaut est False.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
