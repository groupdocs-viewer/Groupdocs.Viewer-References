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
| `ValueError` | When `cache` is None. |

### Example

```python
from groupdocs.viewer import ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger

settings = ViewerSettings(logger=ConsoleLogger())
```

## __init__ {#logger}

Initializes a new ViewerSettings instance.

```python
def __init__(self, logger):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| logger | `ILogger` | The logger to use for diagnostic output. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `logger` is None. |

### Example

```python
from groupdocs.viewer import ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger

# Create settings with a console logger
settings = ViewerSettings(logger=ConsoleLogger())
```

### See Also
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
