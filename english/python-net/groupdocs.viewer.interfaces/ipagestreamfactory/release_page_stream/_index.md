---
title: release_page_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 30
---

## release_page_stream {#int-io.RawIOBase}

Releases the stream created by [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream) method.



```python
def release_page_stream(self, page_number, page_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The number of a page. |
| page_stream | io.RawIOBase | Stream created by [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream) method. |



### See Also
* module [`groupdocs.viewer.interfaces`](../../)
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory)
