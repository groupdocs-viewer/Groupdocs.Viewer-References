---
title: "metode get_view_info"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan tampilan dan informasi spesifik dokumen."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Mengembalikan tampilan dan informasi spesifik dokumen.

Pelajari lebih lanjut tentang dokumen - jenis file, jumlah halaman, dan properti spesifik format lainnya:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | `ViewInfoOptions` | Opsi info tampilan. |

**Returns:** Information about view and document specific information.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `options` bernilai None. |
| `PasswordRequiredException` | Ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | Ketika kata sandi yang ditentukan tidak benar. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Lihat Juga
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
