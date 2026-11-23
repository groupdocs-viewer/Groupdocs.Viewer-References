---
title: "طريقة for_html_view"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ كائن ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى HTML."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

يُهيئ كائن ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### مثال

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # إنشاء خيارات معلومات العرض لتنسيق HTML (صفحة واحدة)
    options = ViewInfoOptions.for_html_view(True)

    # تحميل مستند واسترجاع معلومات العرض
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

يُهيئ كائن ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| render_single_page | `bool` | يُمكّن عرض محتوى HTML إلى صفحة واحدة. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# استرجاع معلومات العرض لـ HTML بصفحة واحدة
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### انظر أيضًا
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
