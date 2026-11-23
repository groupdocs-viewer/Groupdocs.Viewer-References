---
title: "الفئة OutlookOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على خيارات عرض ملفات بيانات Outlook."
type: docs
url: /ar/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

يحتوي على خيارات عرض ملفات بيانات Outlook.

للتفاصيل، راجع وثائق GroupDocs.

يعرض نوع OutlookOptions الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | اسم المجلد (مثل Inbox أو Sent Item أو Deleted Items) للعرض. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | الكلمات المفتاحية المستخدمة لتصفية الرسائل. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # قصر عدد العناصر المعروضة لكل مجلد.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
