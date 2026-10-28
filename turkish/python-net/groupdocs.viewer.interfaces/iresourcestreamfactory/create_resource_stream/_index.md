---
title: "create_resource_stream metodu"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çıktı HTML kaynak verilerini yazmak için kullanılan akışı oluşturur."
type: docs
url: /tr/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Çıktı HTML kaynak verilerini yazmak için kullanılan akışı oluşturur.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Bir sayfanın numarası. |
| resource | `Resource` | Yazı tipi, stil, resim veya grafik gibi HTML kaynağı. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Örnek

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Sayfa 1'de bir CSS kaynağı için bir akış oluştur
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Ayrıca Bakınız
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
