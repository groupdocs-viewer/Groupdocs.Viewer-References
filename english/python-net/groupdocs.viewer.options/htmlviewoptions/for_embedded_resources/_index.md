---
title: for_embedded_resources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 20
---

## for_embedded_resources {#}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class.



```python
def for_embedded_resources(self):
    ...
```




## for_embedded_resources {#groupdocs.viewer.interfaces.IPageStreamFactory}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.


### Returns 


New instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with embedded resources.


```python
def for_embedded_resources(self, page_stream_factory):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | groupdocs.viewer.interfaces.IPageStreamFactory | The factory which implements methods for creating and releasing output page stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `page_stream_factory` is null. |




## for_embedded_resources {#System.String}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class.



```python
def for_embedded_resources(self, file_path_format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | System.String | The file path format e.g. 'page_{0}.html'. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path_format` is null or empty. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions)
