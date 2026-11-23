---
title: "فئة ArchiveOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على خيارات لعرض ملفات الأرشيف."
type: docs
url: /ar/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

يحتوي على خيارات لعرض ملفات الأرشيف.

يعرض نوع ArchiveOptions الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | يُهيئ كائنًا من الفئة [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | اسم ملف الأرشيف المعروض. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | المجلد المراد عرضه. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
