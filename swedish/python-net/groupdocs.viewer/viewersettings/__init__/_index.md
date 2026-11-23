---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny ViewerSettings-instans."
type: docs
url: /sv/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Initierar en ny ViewerSettings-instans.

```python
def __init__(self, cache, logger):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cache | `ICache` | Cachen. |
| logger | `ILogger` | Loggaren. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `cache` är None. |

### Exempel

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

Initierar en ny ViewerSettings-instans.

```python
def __init__(self, cache):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cache | `ICache` | Cachen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `cache` är None. |

## __init__ {#logger}

Initierar en ny ViewerSettings-instans.

```python
def __init__(self, logger):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| logger | `ILogger` | Loggaren. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `logger` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Se även
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
