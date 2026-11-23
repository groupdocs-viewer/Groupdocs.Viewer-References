---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari FolderFontSource."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Menginisialisasi sebuah instance baru dari [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| folder_path | `str` | Jalur ke folder yang berisi font TrueType. |
| search_option | `SearchOption` | Menentukan apakah hanya mencari folder saat ini atau folder saat ini dan semua sub‑folder. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `folder_path` bernilai None. |
| `FileNotFoundError` | Jika jalur yang ditentukan dalam `folder_path` tidak dapat ditemukan. |

### Contoh

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Daftarkan sumber font untuk rendering
FontSettings.set_font_sources(src1, src2)

# Setelah selesai, reset untuk menghindari kebocoran sumber
FontSettings.reset_font_sources()
```

### Lihat Juga
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
