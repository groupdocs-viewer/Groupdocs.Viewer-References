---
title: "create_page_stream yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturur."
type: docs
url: /tr/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturur.

```python
def create_page_stream(self, page_number):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Bir sayfanın numarası. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Örnek

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### Ayrıca Bakınız
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
