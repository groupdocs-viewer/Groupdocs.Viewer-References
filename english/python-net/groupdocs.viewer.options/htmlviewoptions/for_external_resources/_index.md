---
title: for_external_resources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 30
---

## for_external_resources {#}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class.



```python
def for_external_resources(self):
    ...
```




## for_external_resources {#groupdocs.viewer.interfaces.IPageStreamFactory-groupdocs.viewer.interfaces.IResourceStreamFactory}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.


### Returns 


New instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class for rendering into HTML with external resources.


```python
def for_external_resources(self, page_stream_factory, resource_stream_factory):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_stream_factory | groupdocs.viewer.interfaces.IPageStreamFactory | The factory which implements methods for creating and releasing output page stream. |
| resource_stream_factory | groupdocs.viewer.interfaces.IResourceStreamFactory | The factory which implements methods that are required for creating resource URL, instantiating and releasing output HTML resource stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `page_stream_factory` is null. |
| ArgumentNullException | Thrown when `resource_stream_factory` is null. |




## for_external_resources {#System.String-System.String-System.String}

Initializes an instance of the [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions) class.



```python
def for_external_resources(self, file_path_format, resource_file_path_format, resource_url_format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path_format | System.String | The file path format e.g. 'page_{0}.html'. |
| resource_file_path_format | System.String | The resource file path format e.g. 'page_{0}/resource_{1}'. |
| resource_url_format | System.String | The resource URL format e.g. 'page_{0}/resource_{1}'. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path_format` is null or empty. |
| ArgumentException | Thrown when `resource_file_path_format` is null or empty. |
| ArgumentException | Thrown when `resource_url_format` is null or empty. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions)
