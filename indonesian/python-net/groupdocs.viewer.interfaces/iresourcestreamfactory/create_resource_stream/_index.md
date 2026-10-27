---
title: "metode create_resource_stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Membuat aliran yang digunakan untuk menulis data sumber daya HTML output."
type: docs
url: /id/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Membuat aliran yang digunakan untuk menulis data sumber daya HTML output.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |
| resource | `Resource` | Sumber daya HTML seperti font, gaya, gambar, atau grafik. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Contoh

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Buat aliran untuk sumber daya CSS pada halaman 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Lihat Juga
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
