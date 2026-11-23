---
title: "release_resource_stream yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "IResourceStreamFactory.createresourcestream yöntemi tarafından oluşturulan akışı serbest bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

[`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) yöntemi tarafından oluşturulan akışı serbest bırakır.

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Bir sayfanın numarası. |
| resource | `Resource` | Yazı tipi, stil, resim veya grafik gibi HTML kaynağı. |
| resource_stream | `io.RawIOBase` | `IResourceStreamFactory.create_resource_stream` yöntemi tarafından oluşturulan akış. |

**Returns:** None.

### Ayrıca Bakınız
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
