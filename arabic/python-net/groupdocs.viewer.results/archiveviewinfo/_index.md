---
title: "فئة ArchiveViewInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل معلومات العرض لملف أرشيف."
type: docs
url: /ar/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

يمثل معلومات العرض لملف أرشيف.

نوع ArchiveViewInfo يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | ينشئ مثيلاً جديدًا من [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | ينشئ مثيلاً جديدًا من ArchiveViewInfo. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | يرجع سلسلة تمثل الكائن الحالي. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | المجلدات الموجودة في ملف الأرشيف. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | نوع الملف. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | قائمة الصفحات للعرض. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### مثال

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
دروس المهام التي تستخدم `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
