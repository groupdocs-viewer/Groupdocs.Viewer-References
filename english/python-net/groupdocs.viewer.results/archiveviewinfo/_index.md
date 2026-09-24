---
title: ArchiveViewInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents view information for an archive file."
type: docs
url: /python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Represents view information for an archive file.

The ArchiveViewInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Initializes a new instance of [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Initializes a new ArchiveViewInfo instance. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returns a string that represents the current object. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properties
| Property | Description |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | The folders contained by the archive file. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | The type of the file. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | The list of pages to view. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Example

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Task guides that use `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
