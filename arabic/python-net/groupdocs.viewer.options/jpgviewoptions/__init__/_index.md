---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثلاً من فئة JpgViewOptions."
type: docs
url: /ar/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

يُنشئ مثلاً من فئة JpgViewOptions.

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, create_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `create_page_stream` قيمتها None. |

## __init__ {#create_page_stream-release_page_stream}

يُنشئ مثلاً من فئة JpgViewOptions.

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | قابل للاستدعاء يقوم بإنشاء تدفق يُستخدم لكتابة بيانات صفحة الإخراج. |
| release_page_stream | `ReleasePageStream` | قابل للاستدعاء يحرر تدفقًا تم إنشاؤه بواسطة الطريقة المعينة للموكل الممرَّة إلى `create_page_stream`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `release_page_stream` يساوي None. |

## __init__ {#page_stream_factory}

يُنشئ مثلاً من فئة [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

للحصول على مثال على الشيفرة، راجع الوثائق على https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | المصنع الذي يُنفّذ طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `page_stream_factory` يساوي None. |

## __init__

يُنشئ مثلاً من JpgViewOptions.

يقوم هذا المُنشئ بتهيئة نسخة من [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) باستخدام `\"p_{0}.jpg\"` كتنسيق مسار الملف للملفات الناتجة. تُوضع الملفات الناتجة في دليل العمل الحالي للتطبيق.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

يُنشئ مثلاً جديدًا من [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, file_path_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path_format | `str` | تنسيق مسار الملف، مثال `'page_{0}.jpg'`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_path_format` يساوي None أو فارغًا. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # تحميل مستند (مثلاً ملف Excel)
    with Viewer("invoice.xlsx") as viewer:
        # إنشاء خيارات عرض JPEG باستخدام نمط اسم ملف.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### انظر أيضًا
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
