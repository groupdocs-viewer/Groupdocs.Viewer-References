---
title: "proprietà tiles"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Le regioni di disegno da renderizzare."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/tiles/
is_root: false
weight: 2090
---


## tiles property

Le regioni di disegno da renderizzare.

Questa opzione è disponibile solo per i tipi di file [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/) e [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/). Le opzioni [`CadOptions.render_layouts`](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) e [`CadOptions.layout_name`](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) vengono ignorate quando si renderizza per tile.

### Definition:
```python
@property
def tiles(self):
    ...
@tiles.setter
def tiles(self, value):
    ...
```

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
