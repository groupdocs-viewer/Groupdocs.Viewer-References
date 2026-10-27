---
title: "propriété render_text_as_image"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "L'option active le rendu du texte des fichiers PDF sous forme d'image dans la sortie HTML."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

L'option active le rendu du texte des fichiers PDF sous forme d'image dans la sortie HTML.

Lorsque cette option est définie sur True, GroupDocs.Viewer rend le texte sous forme d'image dans la sortie HTML. Cela rend le texte non sélectionnable et améliore le rendu des caractères, assurant une apparence similaire à un PDF dans HTML. La valeur par défaut est False.

Cette option est disponible pour le rendu vers HTML.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
