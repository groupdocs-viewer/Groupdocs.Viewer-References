---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة جديدة من فئة Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

يُنشئ مثيلًا جديدًا من فئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

المزيد من المعلومات

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | الطريقة التي تُعيد تدفقًا قابلاً للقراءة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرفع عندما تكون `get_file_stream` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | الطريقة التي تُعيد تدفقًا قابلاً للقراءة. |
| get_load_options | `Func[LoadOptions]` | الطريقة التي تُعيد خيارات تحميل المستند. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُطرح عندما تكون `get_load_options` None. |
| `Remarks` | - مزيد من المعلومات حول أنواع الملفات المدعومة من قبل GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - مزيد من المعلومات حول ميزات GroupDocs.Viewer لـ .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - مزيد من المعلومات حول تحميل المستندات المشفرة وعرض الملفات من التخزينات الطرفية مع GroupDocs.Viewer لـ .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | الطريقة التي تُعيد تدفقًا قابلاً للقراءة. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

يُنشئ مثيلًا جديدًا من Viewer.

مزيد من المعلومات:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | قابل للاستدعاء يُعيد تدفقًا قابلاً للقراءة. |
| get_load_options | `Func[LoadOptions]` | قابل للاستدعاء يُعيد خيارات تحميل المستند. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

يُنشئ مثيلًا جديدًا من الفئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرفع عندما تكون `stream` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

يُنشئ مثيلًا جديدًا من Viewer.

المزيد من المعلومات:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| leave_open | `bool` | True لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا False. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `stream` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

المزيد من المعلومات:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند `load_options` تكون None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

يُنشئ مثيلًا جديدًا من Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |
| leave_open | `bool` | True لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا False. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند `load_options` تكون None. |
| `Remarks` | - مزيد من المعلومات حول أنواع الملفات المدعومة من قبل GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - مزيد من المعلومات حول ميزات GroupDocs.Viewer لـ .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - مزيد من المعلومات حول تحميل المستندات المشفرة وعرض الملفات من التخزينات الخارجية باستخدام GroupDocs.Viewer لـ .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### مثال

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

يُنشئ مثيلًا جديدًا من Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

يُنشئ مثيلًا جديدًا من Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| settings | `ViewerSettings` | إعدادات Viewer. |
| leave_open | `bool` | True لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا False. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

يُنشئ مثيلًا جديدًا من Viewer.

يتطلب المُنشئ تدفق ملف (`io.RawIOBase`) ويقبل اختياريًا خيارات تحميل المستند وإعدادات Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `stream` أو `load_options` أو `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer

# افتح ملفًا كتيار ثنائي وأنشئ Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # استخدم viewer، على سبيل المثال، قم بالتحويل إلى HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

المزيد من المعلومات:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| load_options | `LoadOptions` | خيارات تحميل المستند. |
| settings | `ViewerSettings` | إعدادات Viewer. |
| leave_open | `bool` | True لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا False. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

يُنشئ مثيلًا جديدًا من فئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | المسار إلى الملف المراد تحويله. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_path` `None` أو فارغًا. |

### مثال

```python
from groupdocs.viewer import Viewer

# ابدأ viewer باستخدام مسار المستند
with Viewer("./sample.docx") as viewer:
    # viewer جاهز لتحويل المستند
    pass
```

## __init__ {#file_path-settings}

يُنشئ مثيلًا جديدًا من الفئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

المزيد من المعلومات:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | المسار إلى الملف المراد تحويله. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `settings` null. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | المسار إلى الملف المراد تحويله. |
| load_options | `LoadOptions` | الخيارات المستخدمة لفتح الملف. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `load_options` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

يُنشئ مثيلًا جديدًا من Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | المسار إلى الملف المراد تحويله. |
| load_options | `LoadOptions` | الخيارات المستخدمة لفتح الملف. |
| settings | `ViewerSettings` | إعدادات Viewer. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `settings` None. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
