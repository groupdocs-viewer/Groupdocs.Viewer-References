---
title: "propriété layout_name"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Le nom de la mise en page spécifique à rendre."
type: docs
url: /fr/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

Le nom de la disposition spécifique à rendre. Le nom de la disposition est sensible à la casse.

Cette option n'est disponible que pour les dessins CAD qui prennent en charge les mises en page : [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), et [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); par défaut, seul le Model est rendu.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### Voir aussi
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
