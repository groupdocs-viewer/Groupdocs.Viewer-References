---
title: "propriété fonts_to_exclude"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La liste des noms de polices à exclure du document HTML."
type: docs
url: /fr/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

La liste des noms de polices à exclure du document HTML.

Les polices ajoutées au document HTML améliorent la stabilité de la vue de sortie, tout en augmentant la taille du résultat du rendu. Cette option vous permet de trouver un équilibre entre stabilité et taille du résultat. Incluez les noms de polices qui sont populaires et installés sur la plupart des systèmes.

Veuillez noter que cette propriété n'est active que lorsque l'option [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) est désactivée.

Pour plus de détails et un exemple de code, consultez la documentation.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Voir aussi
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
