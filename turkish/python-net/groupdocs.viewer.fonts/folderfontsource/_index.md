---
title: "FolderFontSource sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "TrueType yazı tiplerini içeren klasörü temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

TrueType yazı tiplerini içeren klasörü temsil eder.

FolderFontSource türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Yeni bir [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Mevcut FolderFontSource'un belirtilen FolderFontSource nesnesiyle aynı olup olmadığını belirler. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Mevcut FolderFontSource'un belirtilen nesneyle aynı olup olmadığını belirler. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Mevcut [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) nesnesi için hash kodunu döndürür. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Mevcut nesneyi temsil eden bir dize döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | TrueType yazı tiplerini içeren klasörün yolu. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Mevcut klasörü, ya da mevcut klasör ve tüm alt klasörleri aramayı belirten arama seçeneği. |

### Örnek

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Tüm alt klasörleri arayan bir yazı tipi kaynağı oluştur.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
