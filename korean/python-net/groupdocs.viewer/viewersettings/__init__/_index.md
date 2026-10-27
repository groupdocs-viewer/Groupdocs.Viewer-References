---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 ViewerSettings 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

새 ViewerSettings 인스턴스를 초기화합니다.

```python
def __init__(self, cache, logger):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cache | `ICache` | 캐시입니다. |
| logger | `ILogger` | 로거입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `cache`가 None인 경우 발생합니다. |

### 예시

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

새 ViewerSettings 인스턴스를 초기화합니다.

```python
def __init__(self, cache):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cache | `ICache` | 캐시입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `cache`가 None인 경우 발생합니다. |

## __init__ {#logger}

새 ViewerSettings 인스턴스를 초기화합니다.

```python
def __init__(self, logger):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| logger | `ILogger` | 로거입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `logger`가 None인 경우 발생합니다. |

### 예시

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### 참고
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
