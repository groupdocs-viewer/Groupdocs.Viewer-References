---
title: "SpreadsheetFontInfo kelas"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menangkap metainfo dan data biner sebuah font dari dokumen spreadsheet yang dimuat ke dalam instance Viewer."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Mengkapsulkan metainfo dan data biner dari font dalam dokumen spreadsheet yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Dokumen spreadsheet tidak dapat memiliki font yang disematkan, sehingga font yang dikembalikan oleh [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) diinstal pada sistem operasi tempat viewer berjalan.

Tipe SpreadsheetFontInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Menyerialkan info font sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Set karakter dari font ini. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Warna font ini. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Konten font ini sebagai array byte. Jika hanya metainfo tentang font ini yang tersedia dan konten binernya tidak tersedia, properti ini mengembalikan None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Nama keluarga font, tanpa gaya, tidak pernah null atau string kosong. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Format font ini. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Font ini memiliki satu garis coret. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Font ini memiliki garis bawah. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Gaya font ini — dapat berupa Regular, Bold, Italic, atau Bold Italic. |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
