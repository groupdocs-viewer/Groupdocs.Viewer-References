---
title: "Kelas FolderFontSource"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili folder yang berisi font TrueType."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Mewakili folder yang berisi font TrueType.

Tipe FolderFontSource menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Menginisialisasi sebuah instance baru dari [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Menentukan apakah FolderFontSource saat ini sama dengan objek FolderFontSource yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Menentukan apakah FolderFontSource saat ini sama dengan objek yang ditentukan. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Mengembalikan kode hash untuk objek [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) saat ini. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Mengembalikan string yang merepresentasikan objek saat ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Jalur ke folder yang berisi font TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Opsi pencarian yang menentukan apakah mencari di folder saat ini, atau folder saat ini dan semua subfolder. |

### Contoh

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Buat sumber font yang mencari di semua subfolder.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Lihat Juga
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
