---
title: "propriété render_notes"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété active le rendu des notes et des annotations pour certains formats."
type: docs
url: /fr/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

La propriété active le rendu des notes et des annotations pour certains formats.

Certains formats, tels que les présentations ou les fichiers Microsoft Project, peuvent contenir des notes. De plus, les fichiers PDF peuvent comporter des annotations contextuelles (infobulles) qui sont masquées par défaut et ne sont visibles dans un visualiseur PDF que lorsque le curseur de la souris les survole. Par défaut, GroupDocs.Viewer ne rend pas ces notes et annotations (`False`). Pour ce faire, définissez cette propriété sur `True`.

Pour un exemple de code, consultez la documentation.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Voir aussi
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
