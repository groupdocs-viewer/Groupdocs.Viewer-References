---
title: "release_page_stream yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "IPageStreamFactory.createpagestream yöntemi tarafından oluşturulan akışı serbest bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

[`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) yöntemi tarafından oluşturulan akışı serbest bırakır.

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Bir sayfanın numarası. |
| page_stream | `io.RawIOBase` | `IPageStreamFactory.create_page_stream` yöntemi tarafından oluşturulan akış. |

### Ayrıca Bakınız
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
