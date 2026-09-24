---
title: ArchiveOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Contains options for rendering the archive files."
type: docs
url: /python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Contains options for rendering the archive files.

The ArchiveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Initializes an instance of the [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | The displayed archive file name. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | The folder to be rendered. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
