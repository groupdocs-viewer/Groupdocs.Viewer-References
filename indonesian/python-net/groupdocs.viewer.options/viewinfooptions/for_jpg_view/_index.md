---
title: "metode for_jpg_view"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance ViewInfoOptions untuk mengambil informasi tampilan saat merender ke JPG."
type: docs
url: /id/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Menginisialisasi sebuah instance [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) untuk mengambil informasi tampilan saat merender ke JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

Menginisialisasi instance ViewInfoOptions untuk mengambil informasi tampilan saat merender ke JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extract_text | `bool` | Mengaktifkan ekstraksi teks. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Lihat Juga
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
