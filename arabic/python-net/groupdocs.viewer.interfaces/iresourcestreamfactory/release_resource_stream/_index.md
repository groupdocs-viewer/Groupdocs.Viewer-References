---
title: "طريقة release_resource_stream"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يطلق التدفق الذي تم إنشاؤه بواسطة طريقة IResourceStreamFactory.createresourcestream."
type: docs
url: /ar/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

يطلق التدفق الذي تم إنشاؤه بواسطة طريقة [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |
| resource | `Resource` | مورد HTML مثل الخط، النمط، الصورة أو الرسومات. |
| resource_stream | `io.RawIOBase` | التدفق الذي تم إنشاؤه بواسطة طريقة `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### انظر أيضًا
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
