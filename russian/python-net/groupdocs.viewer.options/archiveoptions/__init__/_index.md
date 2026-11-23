---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса ArchiveOptions."
type: docs
url: /ru/python-net/groupdocs.viewer.options/archiveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует экземпляр класса [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/).

```python
def __init__(self):
    ...
```

### Пример

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

### См. также
* class [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/)
