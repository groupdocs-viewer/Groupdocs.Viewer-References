---
title: "طريقة for_external_resources"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة كائن من الفئة HtmlViewOptions لتصيير إلى HTML مع الموارد الخارجية."
type: docs
url: /ar/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

يقوم بتهيئة كائن من الفئة [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) لتصيير إلى HTML مع الموارد الخارجية.

للحصول على مثال الكود، راجع الوثائق.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| create_resource_stream | `CreateResourceStream` | الطريقة التي تُطلق الدفق الذي أنشأته طريقة `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | الطريقة التي تنشئ عنوان URL لمورد HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `create_resource_url` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

يقوم بتهيئة كائن من الفئة HtmlViewOptions لتصيير إلى HTML مع الموارد الخارجية.

لمزيد من أمثلة الاستخدام، راجع توثيق GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | الطريقة التي تنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |
| create_resource_stream | `CreateResourceStream` | الطريقة التي تنشئ دفقًا يُستخدم لكتابة بيانات مورد HTML الناتج. |
| create_resource_url | `CreateResourceUrl` | الطريقة التي تنشئ عنوان URL لمورد HTML. |
| release_page_stream | `ReleasePageStream` | الطريقة التي تُطلق الدفق الذي أنشأه المفوض الممرَّ إلى `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | الطريقة التي تُطلق الدفق الذي أنشأه المفوض الممرَّ إلى `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `release_resource_stream` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # تحميل جدول بيانات Excel
    with Viewer("invoice.xlsx") as viewer:
        # تحويل جدول البيانات إلى HTML مع موارد خارجية.
        # يتم استبدال {0} و {1} برقم الصفحة الحالي واسم المورد، على التوالي.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

يقوم بتهيئة كائن HtmlViewOptions لتصيير إلى HTML مع الموارد الخارجية.

لمزيد من التفاصيل، راجع التوثيق عبر الإنترنت.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | المصنع الذي يطبق طرقًا لإنشاء وإطلاق دفق صفحة الإخراج. |
| resource_stream_factory | `IResourceStreamFactory` | المصنع الذي يطبق الطرق المطلوبة لإنشاء عناوين URL للموارد، وإنشاء وإطلاق تدفقات موارد HTML الناتجة. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `resource_stream_factory` هو None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # إنشاء ملف HTML لكل صفحة وتخزين الموارد الخارجية بشكل منفصل.
    # يتم استبدال {0} و {1} برقم الصفحة الحالي واسم المورد، على التوالي.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

يقوم بتهيئة كائن HtmlViewOptions مُكوَّن لتوليد ملفات HTML مع الموارد الخارجية.

يستخدم الكائن سلاسل التنسيق المقدمة:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

يتم وضع ملفات الإخراج في دليل العمل الحالي للتطبيق.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

يقوم بتهيئة كائن من الفئة [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

للحصول على مثال الكود، راجع الوثائق.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path_format | `str` | تنسيق مسار الملف، مثال `'page_{0}.html'`. |
| resource_file_path_format | `str` | تنسيق مسار ملف المورد، مثال `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | تنسيق URL المورد، مثال `'page_{0}/resource_{1}'`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `resource_url_format` هو None أو فارغ. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # تحميل مستند وتصيير كل صفحة إلى ملف HTML مع الموارد الخارجية.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### انظر أيضًا
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
