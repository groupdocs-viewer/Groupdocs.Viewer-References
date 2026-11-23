---
title: "metode create_page_stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Membuat aliran yang digunakan untuk menulis data halaman output."
type: docs
url: /id/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Membuat aliran yang digunakan untuk menulis data halaman output.

```python
def create_page_stream(self, page_number):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Contoh

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

### Lihat Juga
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
