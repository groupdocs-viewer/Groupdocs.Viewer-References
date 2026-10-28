---
title: "set_font_sources yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belgeleri işlerken TrueType yazı tiplerini aramak için kaynakları ayarlar."
type: docs
url: /tr/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Belgeleri işlerken TrueType yazı tiplerini aramak için kaynakları ayarlar.

Bu yöntem, tek tek [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) nesnelerinin, bunların listelerinin veya her ikisinin bir karışımının herhangi bir kombinasyonunu kabul eder; tüm girdiler uygulanmadan önce tek bir listeye düzleştirilir. Dize yolları olduğu gibi geçirilir ve karakterlere bölünmez.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Yazı tipi kaynakları. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `font_sources` None olduğunda. |

### Örnek

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# tek liste
FontSettings.set_font_sources([src1, src2])
# birden çok liste (düzleştirilmiş)
FontSettings.set_font_sources([src1], [src2])
# karışık — ayrıca düzleştirilmiş
FontSettings.set_font_sources([src1, src2], src2)
```

### Ayrıca Bakınız
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
