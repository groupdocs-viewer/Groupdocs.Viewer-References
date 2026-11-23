---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di ViewerSettings."
type: docs
url: /it/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Inizializza una nuova istanza di ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cache | `ICache` | La cache. |
| logger | `ILogger` | Il logger. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Sollevato quando `cache` è None. |

### Esempio

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

Inizializza una nuova istanza di ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cache | `ICache` | La cache. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Sollevato quando `cache` è None. |

## __init__ {#logger}

Inizializza una nuova istanza di ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| logger | `ILogger` | Il logger. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Sollevato quando `logger` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Vedi anche
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
