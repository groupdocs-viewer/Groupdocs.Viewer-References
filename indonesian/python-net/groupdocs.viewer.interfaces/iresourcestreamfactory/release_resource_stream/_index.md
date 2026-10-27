---
title: "metode release_resource_stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Melepaskan aliran yang dibuat oleh metode IResourceStreamFactory.createresourcestream."
type: docs
url: /id/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Melepaskan aliran yang dibuat oleh metode [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |
| resource | `Resource` | Sumber daya HTML seperti font, gaya, gambar, atau grafik. |
| resource_stream | `io.RawIOBase` | Aliran yang dibuat oleh metode `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### Lihat Juga
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
