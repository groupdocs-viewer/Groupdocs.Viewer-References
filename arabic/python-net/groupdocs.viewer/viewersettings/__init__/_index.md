---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ نسخة جديدة من ViewerSettings."
type: docs
url: /ar/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

يُنشئ نسخة جديدة من ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| cache | `ICache` | ذاكرة التخزين المؤقت. |
| logger | `ILogger` | المسجل. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `cache` None. |

### مثال

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

## __init__ {#cache}

يُنشئ نسخة جديدة من ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| cache | `ICache` | ذاكرة التخزين المؤقت. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `cache` None. |

## __init__ {#logger}

يُنشئ نسخة جديدة من ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| logger | `ILogger` | المسجل. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `logger` None. |

### مثال

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### انظر أيضًا
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
