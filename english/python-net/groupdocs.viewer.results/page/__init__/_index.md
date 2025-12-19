---
title: Page constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page) class.



```python
def __init__(self):
    ...
```




## __init__ {#int-bool}

Initializes new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page) class.



```python
def __init__(self, number, visible):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| visible | bool | The page visibility indicator. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |




## __init__ {#int-System.String-bool}

Initializes new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page) class.



```python
def __init__(self, number, name, visible):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| name | System.String | The worksheet or page name. |
| visible | bool | The page visibility indicator. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |




## __init__ {#int-bool-int-int}

Initializes new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page) class.



```python
def __init__(self, number, visible, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| visible | bool | The page visibility indicator. |
| width | int | The width of the page in pixels when viewing as JPG or PNG. |
| height | int | The height of the page in pixels when viewing as JPG or PNG. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |
| ArgumentException | Thrown when `width` is less or equal to zero. |
| ArgumentException | Thrown when `height` is less or equal to zero. |




## __init__ {#int-System.String-bool-int-int}

Initializes new instance of [`Page`](/viewer/python-net/groupdocs.viewer.results/page) class.



```python
def __init__(self, number, name, visible, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int | The page number. |
| name | System.String | The worksheet or page name. |
| visible | bool | The page visibility indicator. |
| width | int | The width of the page in pixels when viewing as JPG or PNG. |
| height | int | The height of the page in pixels when viewing as JPG or PNG. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `number` is less or equal to zero. |
| ArgumentException | Thrown when `width` is less or equal to zero. |
| ArgumentException | Thrown when `height` is less or equal to zero. |




## __init__ {#int-bool-int-int-System.Collections.Generic.List`1[[GroupDocs.Viewer.Results.Line]]}

Constructs a new instance of Page



```python
def __init__(self, number, visible, width, height, lines):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int |  |
| visible | bool |  |
| width | int |  |
| height | int |  |
| lines | System.Collections.Generic.List`1[[GroupDocs.Viewer.Results.Line]] |  |


## __init__ {#int-System.String-bool-int-int-System.Collections.Generic.List`1[[GroupDocs.Viewer.Results.Line]]}

Constructs a new instance of Page



```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| number | int |  |
| name | System.String |  |
| visible | bool |  |
| width | int |  |
| height | int |  |
| lines | System.Collections.Generic.List`1[[GroupDocs.Viewer.Results.Line]] |  |



### See Also
* module [`groupdocs.viewer.results`](../../)
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page)
