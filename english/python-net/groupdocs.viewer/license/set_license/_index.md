---
title: set_license method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 20
---

## set_license {#io.RawIOBase}

Licenses the component.



```python
def set_license(self, license_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_stream | io.RawIOBase | The license stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `license_stream` is null. |



### Example 


The following example demonstrates how to set a license
passing Stream of the license file.


## set_license {#System.String}

Licenses the component.



```python
def set_license(self, license_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| license_path | System.String | The license file path. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `license_path` is null or empty string. |



### Example 


The following example demonstrates how to set a license 
passing a path to the license file.



### See Also
* module [`groupdocs.viewer`](../../)
* class [`License`](/viewer/python-net/groupdocs.viewer/license)
