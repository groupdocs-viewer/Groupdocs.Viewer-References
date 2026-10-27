---
title: "metode set_font_sources"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menetapkan sumber untuk mencari font TrueType saat merender dokumen."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Menetapkan sumber untuk mencari font TrueType saat merender dokumen.

Metode ini menerima kombinasi apa pun dari objek [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) individual, daftar mereka, atau campuran keduanya; semua masukan diratakan menjadi satu daftar sebelum diterapkan. Jalur string diteruskan apa adanya dan tidak dipisah menjadi karakter.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Sumber font. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `font_sources` bernilai None. |

### Contoh

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# daftar tunggal
FontSettings.set_font_sources([src1, src2])
# beberapa daftar (datar)
FontSettings.set_font_sources([src1], [src2])
# campuran — juga datar
FontSettings.set_font_sources([src1, src2], src2)
```

### Lihat Juga
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
