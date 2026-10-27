---
title: "kelas CadOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Opsi untuk merender gambar CAD."
type: docs
url: /id/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Opsi untuk merender gambar CAD.

Untuk informasi lebih lanjut dan contoh kode, lihat Render CAD drawings and models as HTML, PDF, and image files serta Specify rendering options for CAD files dokumentasi.

Tipe CadOptions menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan tinggi. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan faktor skala. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Menginisialisasi sebuah instance dari kelas [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) untuk rendering berdasarkan lebar. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Menginisialisasi sebuah instance dari kelas CadOptions untuk rendering berdasarkan lebar dan tinggi. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Warna latar belakang gambar. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Bendera yang mengaktifkan mode konversi berorientasi kinerja untuk semua format CAD, di mana mengaturnya ke True mempercepat konversi dengan mengorbankan kualitas output yang berkurang; defaultnya False untuk kualitas maksimum. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Tinggi hasil output (dalam piksel). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Lapisan gambar CAD yang akan dirender. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Nama tata letak spesifik yang akan dirender. Nama tata letak bersifat case-sensitive. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | File konfigurasi plotter PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Bendera yang menunjukkan apakah tata letak dari dokumen CAD harus dirender. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Faktor skala. Nilai lebih besar dari 1 memperbesar hasil output; nilai antara 0 dan 1 mengurangi hasil output. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Wilayah gambar yang akan dirender. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Lebar hasil output (dalam piksel). |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Muat file CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Render berdasarkan lebar dan aktifkan mode kinerja
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
