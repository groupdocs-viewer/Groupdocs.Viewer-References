---
title: get_view_info method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 40
---

## get_view_info {#groupdocs.viewer.options.ViewInfoOptions}

Returns information about view and document specific information.


### Returns 


Information about view and document specific information.


```python
def get_view_info(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | groupdocs.viewer.options.ViewInfoOptions | The view info options. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `options` is null. |
| [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception) | Thrown when password is required to open the document. |
| [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception) | Thrown when password that was specified is incorrect. |





### See Also
* module [`groupdocs.viewer`](../../)
* class [`IncorrectPasswordException`](/viewer/python-net/groupdocs.viewer.exceptions/incorrectpasswordexception)
* class [`PasswordRequiredException`](/viewer/python-net/groupdocs.viewer.exceptions/passwordrequiredexception)
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo)
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer)
