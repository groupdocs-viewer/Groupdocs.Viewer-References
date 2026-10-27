---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثيلًا جديدًا من FolderFontSource."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

يُنشئ مثلاً جديداً من [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| folder_path | `str` | المسار إلى المجلد الذي يحتوي على خطوط TrueType. |
| search_option | `SearchOption` | يحدد ما إذا كان سيتم البحث في المجلد الحالي فقط أو في المجلد الحالي وجميع المجلدات الفرعية. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `folder_path` يساوي None. |
| `FileNotFoundError` | إذا تعذر العثور على المسار المحدد في `folder_path`. |

### مثال

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# تسجيل مصادر الخطوط للعرض
FontSettings.set_font_sources(src1, src2)

# عند الانتهاء، أعد الضبط لتجنب تسرب المصادر.
FontSettings.reset_font_sources()
```

### انظر أيضًا
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
