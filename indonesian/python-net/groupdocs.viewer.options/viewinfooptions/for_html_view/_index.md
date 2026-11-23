---
title: "metode for_html_view"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance ViewInfoOptions untuk mengambil informasi tampilan saat merender ke HTML."
type: docs
url: /id/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Menginisialisasi instance ViewInfoOptions untuk mengambil informasi tampilan saat merender ke HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Contoh

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Buat opsi info tampilan untuk format HTML (satu halaman)
    options = ViewInfoOptions.for_html_view(True)

    # Muat dokumen dan ambil informasi tampilan
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Menginisialisasi instance ViewInfoOptions untuk mengambil informasi tampilan saat merender ke HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| render_single_page | `bool` | Mengaktifkan rendering konten HTML ke satu halaman. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Ambil informasi tampilan untuk HTML dengan satu halaman
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Lihat Juga
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
