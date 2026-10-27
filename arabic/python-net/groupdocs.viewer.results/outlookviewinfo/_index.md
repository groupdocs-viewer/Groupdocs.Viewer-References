---
title: "فئة OutlookViewInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل معلومات العرض لملف بيانات Outlook."
type: docs
url: /ar/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

يمثل معلومات العرض لملف بيانات Outlook.

يعرض نوع OutlookViewInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | يُنشئ مثلاً جديدًا من [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | يُنشئ مثالًا جديدًا من OutlookViewInfo. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | يرجع سلسلة تمثل الكائن الحالي. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | قائمة المجلدات الموجودة في ملف بيانات Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | نوع الملف. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | قائمة الصفحات للعرض. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### مثال

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
دليل المهام الذي يستخدم `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
