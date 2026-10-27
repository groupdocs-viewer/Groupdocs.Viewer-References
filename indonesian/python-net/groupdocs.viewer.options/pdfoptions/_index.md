---
title: "Kelas PdfOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili opsi untuk merender ke dokumen PDF."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Mewakili opsi untuk merender ke dokumen PDF.

Untuk detail, lihat dokumentasi.

Tipe PdfOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Menginisialisasi sebuah instance baru dari kelas PdfOptions. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Properti ini menonaktifkan pengelompokan simbol untuk penempatan simbol yang tepat selama perenderan halaman. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Properti ini menonaktifkan perlindungan penyalinan konten saat merender ke HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Properti ini menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Properti ini mengaktifkan petunjuk font. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Properti ini mengaktifkan perenderan teks dan grafik dalam urutan z dokumen PDF asli saat merender ke HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Opsi tata letak tetap mengaktifkan perenderan dokumen PDF dan EPUB ke HTML dengan tata letak tetap. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | Kualitas gambar keluaran untuk sumber daya gambar saat merender ke HTML. Kualitas default adalah `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Ukuran halaman keluaran diatur agar sesuai dengan ukuran halaman dokumen PDF sumber. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Opsi ini mengaktifkan perenderan teks dalam file PDF sebagai gambar dalam keluaran HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Properti yang mengaktifkan pembungkus setiap gambar dalam dokumen HTML keluaran dengan tag SVG untuk meningkatkan kualitas keluaran. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Aktifkan petunjuk font saat merender halaman PDF ke gambar.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
