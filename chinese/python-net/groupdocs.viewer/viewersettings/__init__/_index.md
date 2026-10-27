---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 ViewerSettings 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

初始化一个新的 ViewerSettings 实例。

```python
def __init__(self, cache, logger):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cache | `ICache` | 缓存。 |
| logger | `ILogger` | 日志记录器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `cache` 为 None 时抛出。 |

### 示例

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

初始化一个新的 ViewerSettings 实例。

```python
def __init__(self, cache):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cache | `ICache` | 缓存。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `cache` 为 None 时抛出。 |

## __init__ {#logger}

初始化一个新的 ViewerSettings 实例。

```python
def __init__(self, logger):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| logger | `ILogger` | 日志记录器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `logger` 为 None 时抛出。 |

### 示例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### 另见
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
