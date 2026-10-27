---
title: "metode release_page_stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Melepaskan aliran yang dibuat oleh metode IPageStreamFactory.createpagestream."
type: docs
url: /id/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Melepaskan aliran yang dibuat oleh metode [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |
| page_stream | `io.RawIOBase` | Aliran yang dibuat oleh metode `IPageStreamFactory.create_page_stream`. |

### Lihat Juga
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
