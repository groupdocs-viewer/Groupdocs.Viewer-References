---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "FolderFontSource'ın yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Yeni bir [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) örneği başlatır.

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| folder_path | `str` | TrueType yazı tiplerini içeren klasörün yolu. |
| search_option | `SearchOption` | Yalnızca geçerli klasörü mü yoksa geçerli klasörü ve tüm alt klasörleri mi arayacağını belirtir. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `folder_path` None ise. |
| `FileNotFoundError` | `folder_path` içinde belirtilen yol bulunamazsa. |

### Örnek

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Renderleme için yazı tipi kaynaklarını kaydet
FontSettings.set_font_sources(src1, src2)

# İşlem tamamlandığında, kaynak sızıntısını önlemek için sıfırla
FontSettings.reset_font_sources()
```

### Ayrıca Bakınız
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
