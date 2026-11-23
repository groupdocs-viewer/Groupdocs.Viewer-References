---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase ArchiveOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/archiveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una instancia de la clase [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/specific_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Ver también
* class [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/)
