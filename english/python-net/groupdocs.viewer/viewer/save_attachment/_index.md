---
title: save_attachment method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Saves attachment file to destination stream."
type: docs
url: /python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1060
---


## save_attachment {#attachment-destination-cancellation_token}

Saves attachment file to `destination` stream.

```python
def save_attachment(self, attachment, destination, cancellation_token):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| attachment | `Attachment` | The attachment to save. |
| destination | `io.RawIOBase` | A writable stream (`io.RawIOBase`) where the attachment will be written. |
| cancellation_token | `CancellationToken` | Optional cancellation token. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `destination` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When the attachment could not be found. |

## save_attachment {#attachment-destination}

Saves the attachment to the provided writable stream.

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
| `PasswordRequiredException` | When password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When the attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Save to a file path; the wrapper handles opening the file.
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")

        # Or save to a stream for explicit control:
        # import io
        # stream = io.BytesIO()
        # viewer.save_attachment(attachment, stream)
        # data = stream.getvalue()
```

### Aliases

These names call `save_attachment` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `save_attachment_attachment` | `save_attachment_attachment(attachment, destination)`<br>`save_attachment_attachment(attachment, destination, cancellation_token)` |
| `save_attachment_stream` | `save_attachment_stream(attachment, destination)`<br>`save_attachment_stream(attachment, destination, cancellation_token)` |
| `save_attachment_streams` | `save_attachment_streams(attachment, destination)`<br>`save_attachment_streams(attachment, destination, cancellation_token)` |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
