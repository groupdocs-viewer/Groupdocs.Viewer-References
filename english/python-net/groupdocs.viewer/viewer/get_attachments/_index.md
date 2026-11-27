---
title: get_attachments method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns attachments contained by the document."
type: docs
url: /python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Returns attachments contained by the document.

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Raises | Description |
| :- | :- |
| `PasswordRequiredException` | Thrown when password is required to open the document. |
| `IncorrectPasswordException` | Thrown when password that was specified is incorrect. |

### Example

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        print(attachment)
        # Save attachment to a file
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

## get_attachments {#cancellation_token}

Returns attachments contained by the document.

```python
def get_attachments(self, cancellation_token):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cancellation_token | `CancellationToken` | Cancellation token. |

**Returns:** Attachments contained by the document.

| Raises | Description |
| :- | :- |
| `PasswordRequiredException` | Thrown when password is required to open the document. |
| `IncorrectPasswordException` | Thrown when password that was specified is incorrect. |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
