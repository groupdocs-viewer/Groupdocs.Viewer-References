---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe ArchiveOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/archiveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une instance de la classe [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/).

```python
def __init__(self):
    ...
```

### Exemple

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

### Voir aussi
* class [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/)
