---
title: "Kelas WordProcessingSubstitutedFontInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengkapsulkan metainfo dan data biner dari satu font dalam dokumen WordProcessing, yang pada awalnya tidak digunakan dalam dokumen instance Viewer yang dimuat, tetapi berfungsi sebagai font substitusi untuk yang…"
type: docs
url: /id/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Mengkapsulkan metainfo dan data biner dari satu font dalam dokumen WordProcessing, yang awalnya tidak digunakan dalam dokumen instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) yang dimuat, tetapi berfungsi sebagai font substitusi bagi yang tidak dapat ditemukan pada mesin target. Font substitusi hanya ada untuk keluarga format WordProcessing.

Struct tak dapat diubah. Instansinya diproduksi dan dikembalikan oleh API publik [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) dan biasanya tidak boleh dibuat oleh pengguna. Untuk detail, lihat dokumentasi: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Tipe WordProcessingSubstitutedFontInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Menyerialkan info font sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Mengembalikan string debug yang berisi informasi font dalam format "original-name -> substituted-name style, format". |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Konten font yang disubstitusi sebagai array byte. Tidak pernah None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Nama keluarga font yang disubstitusi, tanpa gaya. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Format font yang disubstitusi ini (bukan asli). |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Nama keluarga font asli, yang tidak dapat ditemukan pada mesin target, tanpa gaya. Tidak pernah null atau string kosong. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Gaya font asli — dapat berupa Regular, Bold, Italic, atau Bold Italic. |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
