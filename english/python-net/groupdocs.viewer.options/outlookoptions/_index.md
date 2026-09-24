---
title: OutlookOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Contains options for rendering Outlook data files."
type: docs
url: /python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Contains options for rendering Outlook data files.

For details, see the GroupDocs documentation.

The OutlookOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Properties
| Property | Description |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | The email-address used to filter messages by sender or recipient. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | The name of the folder (e.g. Inbox, Sent Item or Deleted Items) to render. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | The maximum number of messages or items that can be rendered from one folder. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | The keywords used to filter messages. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Limit the number of items rendered per folder.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
