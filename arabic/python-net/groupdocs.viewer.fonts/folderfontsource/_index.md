---
title: "الفئة FolderFontSource"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل المجلد الذي يحتوي على خطوط TrueType."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

يمثل المجلد الذي يحتوي على خطوط TrueType.

يعرض نوع FolderFontSource الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | يُنشئ مثلاً جديداً من [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | يحدد ما إذا كان FolderFontSource الحالي هو نفسه كائن FolderFontSource المحدد. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | يحدد ما إذا كان FolderFontSource الحالي هو نفسه الكائن المحدد. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | يعيد رمز التجزئة (hash code) للكائن الحالي من [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | يعيد سلسلة تمثل الكائن الحالي. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | المسار إلى المجلد الذي يحتوي على خطوط TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | خيار البحث الذي يحدد ما إذا كان سيتم البحث في المجلد الحالي فقط، أو في المجلد الحالي وجميع المجلدات الفرعية. |

### مثال

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# إنشاء مصدر خطوط يبحث في جميع المجلدات الفرعية.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
