---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة مثال من PdfViewOptions."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

يُهيئ مثيلًا من [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

للحصول على مثال الكود، راجع الوثائق على https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات ملف الإخراج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `create_file_stream` يساوي `None`. |

## __init__ {#create_file_stream-release_file_stream}

يُهيئ مثيلًا جديدًا من PdfViewOptions.

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | قابل للاستدعاء يُعيد دفق `io.RawIOBase` يُستخدم لكتابة بيانات ملف الإخراج. |
| release_file_stream | `ReleaseFileStream` | قابل للاستدعاء يُفرج عن الدفق الذي أنشأته الطريقة المعينة إلى `create_file_stream`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `release_file_stream` يساوي None. |

## __init__ {#file_stream_factory}

يُهيئ مثيلًا من PdfViewOptions.

للحصول على مثال الكود، راجع الوثائق: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | المصنع الذي يطبق طرق إنشاء وإطلاق دفق ملف الإخراج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرفع عندما يكون `file_stream_factory` يساوي None. |

## __init__

يُهيئ مثيلًا من PdfViewOptions.

يقوم هذا المُنشئ بتهيئة كائن PdfViewOptions باستخدام `"output.pdf"` كصيغة مسار الملف للملف الناتج. سيتم وضع الملف الناتج في دليل العمل الحالي للتطبيق.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

يُهيئ مثيلًا من الفئة [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

للحصول على مثال الكود، راجع الوثائق.

```python
def __init__(self, output_file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| output_file_path | `str` | مسار ملف PDF الناتج. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `output_file_path` None أو فارغ. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### انظر أيضًا
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
