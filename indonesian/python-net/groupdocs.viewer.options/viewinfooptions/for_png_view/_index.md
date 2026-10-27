---
title: "metode for_png_view"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance kelas ViewInfoOptions untuk mengambil informasi tampilan saat merender ke PNG."
type: docs
url: /id/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Menginisialisasi sebuah instance kelas [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) untuk mengambil informasi tampilan saat merender ke PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Buat opsi informasi tampilan untuk format PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Muat dokumen dan dapatkan informasi tampilan untuk PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Menginisialisasi sebuah instance kelas ViewInfoOptions untuk mengambil informasi tampilan saat merender ke PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extract_text | `bool` | Mengaktifkan ekstraksi teks. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Contoh

```python
from groupdocs.viewer.options import ViewInfoOptions

# Buat opsi informasi tampilan untuk format PNG dengan ekstraksi teks diaktifkan
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Lihat Juga
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
