---
title: release_resource_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 40
---

## release_resource_stream {#int-groupdocs.viewer.results.Resource-io.RawIOBase}

Releases the stream created by [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream) method.



```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The number of a page. |
| resource | groupdocs.viewer.results.Resource | The HTML resource such as font, style, image or graphics. |
| resource_stream | io.RawIOBase | Stream created by [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream) method. |



### See Also
* module [`groupdocs.viewer.interfaces`](../../)
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory)
