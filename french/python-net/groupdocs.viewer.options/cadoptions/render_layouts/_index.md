---
title: "propriété render_layouts"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Le drapeau indiquant si les dispositions du document CAD doivent être rendues."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

Le drapeau indiquant si les dispositions du document CAD doivent être rendues.

Cette option n'est disponible que pour les dessins CAD qui prennent en charge les mises en page [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), et [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Par défaut, seul le Modèle est rendu.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Voir aussi
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
