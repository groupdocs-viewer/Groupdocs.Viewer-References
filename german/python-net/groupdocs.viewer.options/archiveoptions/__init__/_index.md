---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Klasse ArchiveOptions."
type: docs
url: /de/python-net/groupdocs.viewer.options/archiveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine Instanz der [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

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

### Siehe auch
* class [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/)
