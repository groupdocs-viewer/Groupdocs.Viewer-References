---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yeni bir ViewerSettings örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Yeni bir ViewerSettings örneği başlatır.

```python
def __init__(self, cache, logger):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cache | `ICache` | Önbellek. |
| logger | `ILogger` | Günlükleyici. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `cache` None olduğunda yükseltilir. |

### Örnek

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

Yeni bir ViewerSettings örneği başlatır.

```python
def __init__(self, cache):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cache | `ICache` | Önbellek. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `cache` None olduğunda yükseltilir. |

## __init__ {#logger}

Yeni bir ViewerSettings örneği başlatır.

```python
def __init__(self, logger):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| logger | `ILogger` | Günlükleyici. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `logger` None olduğunda yükseltilir. |

### Örnek

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Ayrıca Bakınız
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
