---
title: "طريقة get_view_info"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يعيد العرض ومعلومات محددة للوثيقة."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

يعيد العرض ومعلومات محددة للوثيقة.

تعرف على المزيد حول المستند - نوع الملف، عدد الصفحات والخصائص المحددة للصيغة الأخرى:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `ViewInfoOptions` | خيارات معلومات العرض. |

**Returns:** Information about view and document specific information.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `options` None. |
| `PasswordRequiredException` | عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| `IncorrectPasswordException` | عندما تكون كلمة المرور المحددة غير صحيحة. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
