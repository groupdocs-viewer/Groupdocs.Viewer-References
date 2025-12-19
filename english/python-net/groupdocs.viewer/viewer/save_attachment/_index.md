---
title: save_attachment method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 50
---

## save_attachment {#groupdocs.viewer.results.Attachment-io.RawIOBase}

Saves attachment file to `destination` stream.



```python
def save_attachment(self, attachment, destination):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| attachment | groupdocs.viewer.results.Attachment | The attachment. |
| destination | io.RawIOBase | The writable stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `attachment` is null. |
| ArgumentNullException | Thrown when `destination` is null. |
| [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [`GroupDocsViewerException`](/viewer/python-net/groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |





### See Also
* module [`groupdocs.viewer`](../../)
* class [`GroupDocsViewerException`](/viewer/python-net/groupdocs.viewer.exceptions/groupdocsviewerexception)
* class [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception)
* class [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception)
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer)
