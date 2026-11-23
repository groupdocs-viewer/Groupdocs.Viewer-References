---
title: "Kelas PdfOptimizationOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili opsi optimasi PDF yang diterapkan pada file PDF keluaran."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Mewakili opsi optimasi PDF yang diterapkan pada file PDF keluaran.

Untuk detail dan contoh kode, lihat halaman dokumentasi.

Tipe PdfOptimizationOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Menginisialisasi nilai default opsi MaxResolution menjadi 300 dan opsi ImageQuality menjadi 100. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Properti ini memungkinkan kompresi gambar dalam file PDF keluaran. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Properti ini memungkinkan konversi file PDF keluaran ke skala abu-abu. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Kualitas gambar dalam file PDF keluaran, dinyatakan dalam persentase. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Properti ini memungkinkan optimasi file PDF keluaran untuk dilihat secara daring dengan peramban web. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Resolusi maksimum dalam file PDF keluaran. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Properti yang memungkinkan optimasi spreadsheet dalam file PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Properti ini memungkinkan penghapusan anotasi dari file PDF keluaran. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Properti ini memungkinkan penghapusan bidang formulir dari file PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Properti ini menghapus objek yang tidak terpakai (tertinggal) dari file PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Properti ini menghapus aliran yang tidak terpakai (tertinggal) dari file PDF yang direferensikan dalam kamus sumber daya halaman tetapi tidak pernah digunakan dalam konten halaman. Dinonaktifkan secara default (`False`); mengatur ke `True` mengurangi ukuran PDF keluaran. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Properti ini memungkinkan penetapan resolusi maksimum dalam file PDF keluaran. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Properti ini melakukan subset font dalam file PDF keluaran. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Aktifkan linearization untuk pratinjau web yang lebih cepat
        view_options.pdf_optimization_options.lineriaze = True
        # Hapus anotasi dan bidang formulir untuk mengurangi ukuran
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
