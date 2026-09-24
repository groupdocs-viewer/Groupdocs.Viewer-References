---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new ViewerSettings instance."
type: docs
url: /python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Initializes a new ViewerSettings instance.

```python
def __init__(self, cache, logger):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cache | `ICache` | The cache. |
| logger | `ILogger` | The logger. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `cache` is None. |

### Example

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

Initializes a new ViewerSettings instance.

```python
def __init__(self, cache):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| cache | `ICache` | The cache. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `cache` is None. |

## __init__ {#logger}

Initializes a new ViewerSettings instance.

```python
def __init__(self, logger):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| logger | `ILogger` | The logger. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `logger` is None. |

### Example

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### See Also
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
