---
title: "kelas IFontInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili antarmuka umum untuk semua font yang dapat diekstrak dari semua keluarga format dokumen yang didukung: PDF, WordProcessing, Spreadsheet, dan Presentation."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Mewakili antarmuka umum untuk semua font yang dapat diekstrak dari semua keluarga format dokumen yang didukung: PDF, WordProcessing, Spreadsheet, dan Presentation.

Tipe IFontInfo mengekspos anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Menyerialkan info font ini sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Konten biner font sebagai array byte, jika tersedia, atau None jika tidak. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Nama keluarga font sebagai string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Format font ini sebagai enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, atau `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Gaya font sebagai enum (Regular, Bold, Italic, atau Bold Italic); beberapa format dokumen mungkin hanya mendukung [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
