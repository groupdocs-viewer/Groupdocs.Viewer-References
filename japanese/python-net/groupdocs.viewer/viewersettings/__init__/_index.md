---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい ViewerSettings インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

新しい ViewerSettings インスタンスを初期化します。

```python
def __init__(self, cache, logger):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| cache | `ICache` | キャッシュ。 |
| logger | `ILogger` | ロガー。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `cache` が None のときに発生します。 |

### 例

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

新しい ViewerSettings インスタンスを初期化します。

```python
def __init__(self, cache):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| cache | `ICache` | キャッシュ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `cache` が None のときに発生します。 |

## __init__ {#logger}

新しい ViewerSettings インスタンスを初期化します。

```python
def __init__(self, logger):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| logger | `ILogger` | ロガー。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `logger` が None のときに発生します。 |

### 例

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### 参照
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
