---
title: view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 60
---

## view {#groupdocs.viewer.options.ViewOptions}

Creates view of all document pages.



```python
def view(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | groupdocs.viewer.options.ViewOptions | The view options. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `options` is null. |
| [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [`GroupDocsViewerException`](/viewer/python-net/groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |




## view {#groupdocs.viewer.options.ViewOptions-list}

Creates view of specific document pages.



```python
def view(self, options, page_numbers):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | groupdocs.viewer.options.ViewOptions | The view options. |
| page_numbers | list | The page numbers to view. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `options` is null. |
| ArgumentNullException | Thrown when `page_numbers` is null. |
| ArgumentException | Thrown when `page_numbers` is empty. |
| [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |
| [`GroupDocsViewerException`](/viewer/python-net/groupdocs.viewer.exceptions/groupdocsviewerexception) | Thrown when attachment could not be found. |





### See Also
* module [`groupdocs.viewer`](../../)
* class [`GroupDocsViewerException`](/viewer/python-net/groupdocs.viewer.exceptions/groupdocsviewerexception)
* class [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception)
* class [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception)
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer)
