---
title: "Kelas WordProcessingFontInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengkapsulkan metainfo dan data biner dari sebuah font dari dokumen WordProcessing yang dimuat ke dalam instance Viewer."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Mengkapsulkan metainfo dan data biner dari font dalam dokumen WordProcessing yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Struct tidak dapat diubah.

Instansinya diproduksi dan dikembalikan oleh API publik [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) dan biasanya tidak boleh dibuat oleh pengguna.

Untuk detail, lihat dokumentasi: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Tipe WordProcessingFontInfo menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Menyerialkan info font sebagai at-rule @font-face dan menulisnya ke penulis teks yang ditentukan. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Mengembalikan info debug tentang data font ini dengan templat berikut: "name style, embedded/system, format". |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Nama keluarga alternatif dari font. Jika tidak ada, maka string kosong. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Set karakter dari font ini. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Konten font ini sebagai array byte. Jika hanya metainfo tentang font ini yang tersedia dan konten biner tidak tersedia, properti mengembalikan None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Nama keluarga font, tanpa gaya; tidak pernah None atau string kosong. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Format font ini. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Properti ini menunjukkan apakah font ini tertanam di dalam dokumen, dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), atau merupakan font sistem (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Gaya font — dapat berupa Regular, Bold, Italic, atau Bold Italic. |

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
