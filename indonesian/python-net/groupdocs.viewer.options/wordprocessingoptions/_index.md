---
title: "Kelas WordProcessingOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Berisi opsi untuk merender dokumen Word."
type: docs
url: /id/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Berisi opsi untuk merender dokumen Word.

Untuk detail, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/render-word-documents/.

Tipe WordProcessingOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Menginisialisasi opsi untuk merender dokumen pengolah kata. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Membuat dan mengembalikan salinan mendalam penuh dari opsi-opsi ini. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Menentukan apakah instance [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) yang ditentukan sama dengan instance ini. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Margin bawah halaman. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Opsi ini mengaktifkan kerning dan fitur OpenType lainnya saat merender skrip Arab, Ibrani, Latin berbasis India, atau Cyrillic. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender dokumen WordProcessing ke format PNG atau JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Margin kiri halaman. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Lokasi penomoran halaman untuk dokumen WordProcessing yang dimuat, yang dapat memaksa penerapan penomoran halaman; secara default adalah `WordsPageNumberLocation.not_apply`, sehingga dokumen tetap tidak berubah. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Ukuran halaman output. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Properti ini mengaktifkan perenderan perubahan yang dilacak (revisi). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Margin kanan halaman. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Margin atas halaman dalam poin. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Opsi ini menonaktifkan navigasi dari daftar isi ketika diatur ke True untuk perenderan HTML atau PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Properti ini menentukan apakah bidang dengan tipe tertentu diperbarui sebelum menyimpan dokumen WordProcessing ke format HTML, PDF, PNG, atau JPEG. Defaultnya adalah True, yang berarti bidang diperbarui. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Resolusi vertikal untuk gambar yang dihasilkan dalam dot per inci, digunakan hanya saat merender dokumen WordProcessing ke format PNG atau JPEG. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
