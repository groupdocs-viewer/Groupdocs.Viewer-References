---
title: ProjectManagementViewInfo class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents view information for MS Project document."
type: docs
url: /python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Represents view information for MS Project document.

The ProjectManagementViewInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Initializes a new instance of [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Initializes a new instance of ProjectManagementViewInfo. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returns a string that represents the current object. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properties
| Property | Description |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | The date time when the project is to be completed. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | The date time from which the project started. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | The type of the file. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | The list of pages to view. (inherited from [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Example

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
Task guides that use `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
