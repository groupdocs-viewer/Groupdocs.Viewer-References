---
title: "kelas SpreadsheetOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Opsi untuk merender spreadsheet."
type: docs
url: /id/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Opsi untuk merender spreadsheet.

Untuk detail, lihat anak-anak dari topik Render file spreadsheet.

Tipe SpreadsheetOptions menampilkan anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Menginisialisasi sebuah instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) untuk merender seluruh lembar menjadi satu halaman. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Menginisialisasi sebuah instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) yang dikonfigurasi untuk membagi lembar kerja menjadi halaman berdasarkan pemisah halaman. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Menginisialisasi sebuah instance kelas [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) untuk merender hanya area cetak. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Menginisialisasi sebuah instance kelas [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) untuk merender area cetak dan pemisah halaman. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Menginisialisasi sebuah instance SpreadsheetOptions untuk merender lembar menjadi halaman. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Menginisialisasi sebuah instance SpreadsheetOptions untuk merender lembar menjadi halaman. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | Margin bawah halaman saat mengonversi ke PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Jumlah kolom yang disertakan pada setiap halaman saat membagi lembar kerja menjadi halaman. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Jumlah baris yang disertakan pada setiap halaman saat membagi lembar kerja menjadi halaman. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | Properti ini memungkinkan deteksi pemisah untuk file CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | Resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender spreadsheet ke format PNG atau JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | Margin kiri halaman saat mengonversi ke PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | Properti ini memungkinkan perenderan garis kisi. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | Properti ini memungkinkan perenderan judul. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | Properti ini memungkinkan perenderan kolom tersembunyi. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | Properti ini memungkinkan rendering baris tersembunyi. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | Margin kanan halaman saat mengonversi ke PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | Properti ini menonaktifkan rendering kolom kosong. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | Properti ini menonaktifkan rendering baris kosong. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Mode overflow teks untuk merender dokumen spreadsheet ke HTML. Defaultnya adalah `TextOverflowMode.OverlayIfNextIsEmpty`, yang meniru perilaku default MS Excel. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | Margin atas halaman saat mengonversi ke PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | Resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender spreadsheet ke format PNG atau JPEG. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Aktifkan rendering garis kisi dalam spreadsheet.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
