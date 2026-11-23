---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe ViewerSettings-instantie."
type: docs
url: /nl/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Initialiseert een nieuwe ViewerSettings-instantie.

```python
def __init__(self, cache, logger):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cache | `ICache` | De cache. |
| logger | `ILogger` | De logger. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `cache` None is. |

### Voorbeeld

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

Initialiseert een nieuwe ViewerSettings-instantie.

```python
def __init__(self, cache):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cache | `ICache` | De cache. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `cache` None is. |

## __init__ {#logger}

Initialiseert een nieuwe ViewerSettings-instantie.

```python
def __init__(self, logger):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| logger | `ILogger` | De logger. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `logger` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Zie ook
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
