---
title: "طريقة for_png_view"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ كائنًا من فئة ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى PNG."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

يُهيئ كائنًا من الفئة [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) لاسترجاع معلومات العرض عند التحويل إلى PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# إنشاء خيارات معلومات العرض لتنسيق PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# تحميل مستند والحصول على معلومات العرض لـ PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

يُهيئ كائنًا من فئة ViewInfoOptions لاسترجاع معلومات العرض عند التحويل إلى PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| extract_text | `bool` | يُمكّن استخراج النص. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### مثال

```python
from groupdocs.viewer.options import ViewInfoOptions

# إنشاء خيارات معلومات العرض لتنسيق PNG مع تمكين استخراج النص
options = ViewInfoOptions.for_png_view(extractText=True)
```

### انظر أيضًا
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
