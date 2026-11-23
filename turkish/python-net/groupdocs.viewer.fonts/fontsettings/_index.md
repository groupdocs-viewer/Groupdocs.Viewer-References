---
title: "FontSettings sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "TrueType yazı tiplerini aramak için kaynaklarla çalışmaya yönelik metodlar sağlar."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

TrueType yazı tiplerini aramak için kaynaklarla çalışmaya yönelik metodlar sağlar.

FontSettings türü aşağıdaki üyeleri ortaya çıkarır:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Daha önce ayarlanmış yazı tipi kaynaklarını sıfırlar. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Belgeleri işlerken TrueType yazı tiplerini aramak için kaynakları ayarlar. |

### Örnek

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Çeşitli argüman biçimlerini kullanarak yazı tipi kaynaklarını ayarlayın (içeride düzleştirilir)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Tüm kayıtlı yazı tipi kaynaklarını temizle
FontSettings.reset_font_sources()
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
