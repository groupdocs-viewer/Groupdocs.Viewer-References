---
title: "Kelas PdfFontInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengkapsulkan metadata dan data biner dari font PDF yang dimuat ke dalam instance Viewer, yang mungkin disematkan dalam dokumen atau diinstal pada sistem operasi tempat GroupDocs.Viewer berjalan."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Mengkapsulkan metadata dan data biner dari font PDF yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), yang dapat disematkan dalam dokumen atau diinstal pada sistem operasi tempat GroupDocs.Viewer berjalan.

Tipe PdfFontInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Menyerialkan info font ini sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Konten font ini sebagai array byte, atau None jika hanya metadata yang tersedia dan konten biner tidak tersedia. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Nama keluarga font, tanpa gaya; tidak pernah None atau string kosong. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Format font ini. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Properti ini menunjukkan apakah font disematkan di dalam dokumen PDF dan dimuat ke dalam instance Viewer (`True`), atau tidak. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Properti ini menunjukkan apakah font ini ada (diinstal) di sistem operasi tempat GroupDocs.Viewer berjalan. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Gaya font; dapat berupa Regular, Bold, Italic, atau Bold Italic. |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
