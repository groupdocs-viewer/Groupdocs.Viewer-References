---
title: "طريقة set_font_sources"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يضبط المصادر للبحث عن خطوط TrueType عند عرض المستندات."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

يضبط المصادر للبحث عن خطوط TrueType عند عرض المستندات.

تقبل الطريقة أي تركيبة من كائنات [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) الفردية، أو قوائم منها، أو مزيج من كليهما؛ يتم تسطيح جميع المدخلات إلى قائمة واحدة قبل التطبيق. تُمرّر مسارات السلاسل كما هي ولا يتم تقسيمها إلى أحرف.

```python
def set_font_sources(cls, font_sources):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | مصادر الخط. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `font_sources` None. |

### مثال

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# قائمة واحدة
FontSettings.set_font_sources([src1, src2])
# قوائم متعددة (مسطحة)
FontSettings.set_font_sources([src1], [src2])
# مختلط — مسطح أيضًا
FontSettings.set_font_sources([src1, src2], src2)
```

### انظر أيضًا
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
