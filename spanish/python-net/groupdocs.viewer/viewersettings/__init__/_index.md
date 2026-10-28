---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de ViewerSettings."
type: docs
url: /es/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Inicializa una nueva instancia de ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cache | `ICache` | La caché. |
| logger | `ILogger` | El logger. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `cache` es None. |

### Ejemplo

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

Inicializa una nueva instancia de ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cache | `ICache` | La caché. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `cache` es None. |

## __init__ {#logger}

Inicializa una nueva instancia de ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| logger | `ILogger` | El logger. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `logger` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Ver también
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
