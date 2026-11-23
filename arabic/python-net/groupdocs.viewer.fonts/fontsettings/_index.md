---
title: "FontSettings فئة"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يوفر أساليب للعمل مع المصادر للبحث عن خطوط TrueType."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

يوفر أساليب للعمل مع المصادر للبحث عن خطوط TrueType.

يعرض نوع FontSettings الأعضاء التالية:

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | يعيد ضبط مصادر الخطوط التي تم تعيينها مسبقًا. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | يضبط المصادر للبحث عن خطوط TrueType عند عرض المستندات. |

### مثال

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# تعيين مصادر الخطوط باستخدام صيغ مختلفة للمعاملات (مُسطَّحة داخليًا)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# مسح جميع مصادر الخطوط المسجلة
FontSettings.reset_font_sources()
```

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
