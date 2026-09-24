---
title: save_attachment method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Saves attachment file to destination stream."
type: docs
url: /python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Saves attachment file to `destination` stream.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| attachment | `Attachment` | The attachment. |
| destination | `io.RawIOBase` | The writable stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `destination` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When the attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
