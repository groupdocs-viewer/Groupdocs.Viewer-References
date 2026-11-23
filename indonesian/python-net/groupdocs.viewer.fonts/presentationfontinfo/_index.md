---
title: "Kelas PresentationFontInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili metainfo dan data biner sebuah font dari dokumen Presentation yang dimuat ke dalam instance Viewer."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Mewakili metainfo dan data biner dari font dalam dokumen Presentation yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Font tersebut digunakan dalam konten dokumen dan dapat disematkan dalam dokumen atau diinstal pada sistem operasi tempat viewer berjalan.

Tipe PresentationFontInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Menyerialkan info font ini sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Konten font ini sebagai array byte. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Nama keluarga font, tanpa gaya; tidak pernah None atau string kosong. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Format font ini. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | Properti ini menunjukkan apakah font tersemat di dalam dokumen dan dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), atau merupakan font sistem (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Gaya font — dapat berupa Regular, Bold, Italic, atau Bold Italic. |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
