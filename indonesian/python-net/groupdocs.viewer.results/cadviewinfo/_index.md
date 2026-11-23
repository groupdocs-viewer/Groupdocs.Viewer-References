---
title: "Kelas CadViewInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili informasi tampilan untuk gambar CAD."
type: docs
url: /id/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Mewakili informasi tampilan untuk gambar CAD.

Tipe CadViewInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Menginisialisasi sebuah instance baru CadViewInfo. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Mengembalikan string yang mewakili objek saat ini. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | Daftar lapisan yang terdapat dalam gambar CAD. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | Daftar tata letak yang terdapat dalam gambar CAD. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Tipe file. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Daftar halaman yang akan ditampilkan. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Contoh

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Panduan tugas yang menggunakan `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
