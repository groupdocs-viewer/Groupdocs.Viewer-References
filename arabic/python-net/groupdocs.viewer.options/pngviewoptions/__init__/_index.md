---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثيلاً جديداً من PngViewOptions."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

ينشئ مثيلاً جديدًا لـ [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

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

ينشئ مثيلاً من الفئة [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |
| release_page_stream | `ReleasePageStream` | الطريقة التي تُطلق التدفق الذي أنشأته الطريقة المخصصة للمنفذ الممرَّر إلى معامل `create_page_stream`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `release_page_stream` قيمتها None. |

## __init__ {#page_stream_factory}

ينشئ مثيلاً جديدًا لـ [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

لمزيد من المعلومات، راجع الوثائق.

```python
def __init__(self, page_stream_factory):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | المصنع الذي يُنفّذ طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كانت `page_stream_factory` قيمتها `None`. |

## __init__

ينشئ مثيلاً من PngViewOptions.

هذا المُنشئ ينشئ [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) مع ``\"p_{0}.png\"`` كصيغة مسار الملف الافتراضية للملفات الناتجة. تُحفظ ملفات PNG المُولَّدة في دليل العمل الحالي للتطبيق.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

ينشئ مثيلاً جديدًا لـ [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, file_path_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path_format | `str` | صيغة مسار الملف، مثال: `'page_{0}.png'`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `file_path_format` يساوي None أو فارغًا. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### انظر أيضًا
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
