---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue ViewerSettings-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Initialisiert eine neue ViewerSettings-Instanz.

```python
def __init__(self, cache, logger):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cache | `ICache` | Der Cache. |
| logger | `ILogger` | Der Logger. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `cache` None ist. |

### Beispiel

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

Initialisiert eine neue ViewerSettings-Instanz.

```python
def __init__(self, cache):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cache | `ICache` | Der Cache. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `cache` None ist. |

## __init__ {#logger}

Initialisiert eine neue ViewerSettings-Instanz.

```python
def __init__(self, logger):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| logger | `ILogger` | Der Logger. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `logger` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Siehe auch
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
