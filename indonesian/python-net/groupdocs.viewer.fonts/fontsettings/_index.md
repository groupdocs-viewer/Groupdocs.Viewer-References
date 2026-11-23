---
title: "Kelas FontSettings"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menyediakan metode untuk bekerja dengan sumber guna mencari font TrueType."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Menyediakan metode untuk bekerja dengan sumber guna mencari font TrueType.

Tipe FontSettings menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Mengatur ulang sumber font yang telah disetel sebelumnya. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Menetapkan sumber untuk mencari font TrueType saat merender dokumen. |

### Contoh

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Atur sumber font menggunakan berbagai bentuk argumen (diluruskan secara internal)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Bersihkan semua sumber font yang terdaftar
FontSettings.reset_font_sources()
```

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
