---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de ViewerSettings."
type: docs
url: /fr/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Initialise une nouvelle instance de ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| cache | `ICache` | Le cache. |
| logger | `ILogger` | Le logger. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `cache` est None. |

### Exemple

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

Initialise une nouvelle instance de ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| cache | `ICache` | Le cache. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `cache` est None. |

## __init__ {#logger}

Initialise une nouvelle instance de ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| logger | `ILogger` | Le logger. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `logger` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Voir aussi
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
