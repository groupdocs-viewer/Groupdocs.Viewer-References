---
title: PngViewOptions constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes an instance of the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions) class.



```python
def __init__(self):
    ...
```




## __init__ {#groupdocs.viewer.interfaces.IPageStreamFactory}

Initializes an instance of the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions) class.



```python
def __init__(self, page_stream_factory):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | groupdocs.viewer.interfaces.IPageStreamFactory | The factory which implements methods for creating and releasing output page stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `page_stream_factory` is null. |




## __init__ {#System.String}

Initializes an instance of the [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions) class.



```python
def __init__(self, file_path_format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | System.String | The file path format e.g. 'page_{0}.png'. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path_format` is null or empty. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions)
