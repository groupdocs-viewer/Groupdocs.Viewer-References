---
title: "طريقة for_embedded_resources"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة كائن HtmlViewOptions لتصيير HTML مع الموارد المضمنة."
type: docs
url: /ar/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

يقوم بتهيئة كائن HtmlViewOptions لتصيير HTML مع الموارد المضمنة.

لمزيد من التفاصيل، راجع الوثائق.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `create_page_stream` يساوي None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

يقوم بتهيئة كائن من الفئة [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) لتصيير HTML مع الموارد المضمنة.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| release_page_stream | `ReleasePageStream` | الطريقة التي تُطلق التدفق الذي أنشأته الطريقة المعيّنة للمعامل `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `release_page_stream` يساوي `None`. للحصول على مثال الشيفرة، راجع الوثائق. |

## for_embedded_resources {#page_stream_factory}

يقوم بتهيئة كائن HtmlViewOptions لتصيير إلى HTML مع الموارد المضمنة.

للحصول على مثال الشيفرة، راجع الوثائق على https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | المصنع الذي يُنفّذ طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون page_stream_factory يساوي None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

يقوم بتهيئة كائن من الفئة [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) مع الموارد المضمنة.

للحصول على مثال الكود، راجع الوثائق.

```python
def for_embedded_resources(cls):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

يقوم بتهيئة كائن HtmlViewOptions للموارد المضمنة.

للحصول على مثال الكود، راجع الوثائق.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path_format | `str` | تنسيق مسار الملف مثل 'page_{0}.html'. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `file_path_format` يساوي None أو فارغًا. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### انظر أيضًا
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
