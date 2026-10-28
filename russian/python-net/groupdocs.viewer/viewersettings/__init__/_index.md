---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр ViewerSettings."
type: docs
url: /ru/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Инициализирует новый экземпляр ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| cache | `ICache` | Кеш. |
| logger | `ILogger` | Логгер. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `cache` равно None. |

### Пример

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

Инициализирует новый экземпляр ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| cache | `ICache` | Кеш. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `cache` равно None. |

## __init__ {#logger}

Инициализирует новый экземпляр ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| logger | `ILogger` | Логгер. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Возникает, когда `logger` равно None. |

### Пример

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### См. также
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
