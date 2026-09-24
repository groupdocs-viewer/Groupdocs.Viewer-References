---
title: Attachment class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents an attachment file contained by an email message, archive, PDF document, or Outlook data file."
type: docs
url: /python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Represents an attachment file contained by an email message, archive, PDF document, or Outlook data file.

The Attachment type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Initializes a new [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Initializes a new Attachment instance. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Initializes a new instance of the Attachment class. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Initializes a new instance of the Attachment class. |

### Methods
| Method | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Returns a string that represents the current object. |

### Properties
| Property | Description |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | The attachment file name. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | The attachment relative path, e.g. `folder/file.docx`, or the filename when the file is located in the root of an archive, in an e‑mail message, or a data file. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | The attachment file type. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | The unique identifier of the attachment in the context of a single file that contains this attachment. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | The attachment file size in bytes. |

### Example

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Access attachment properties, e.g., file name
        print(attachment.file_name)
        # Save the attachment to a file path
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### See Also
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
