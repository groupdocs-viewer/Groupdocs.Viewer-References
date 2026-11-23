---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance ViewerSettings baru."
type: docs
url: /id/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Menginisialisasi sebuah instance ViewerSettings baru.

```python
def __init__(self, cache, logger):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cache | `ICache` | Cache. |
| logger | `ILogger` | Logger. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dibuat ketika `cache` bernilai None. |

### Contoh

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

Menginisialisasi sebuah instance ViewerSettings baru.

```python
def __init__(self, cache):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cache | `ICache` | Cache. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dibuat ketika `cache` bernilai None. |

## __init__ {#logger}

Menginisialisasi sebuah instance ViewerSettings baru.

```python
def __init__(self, logger):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| logger | `ILogger` | Logger. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dibuat ketika `logger` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Lihat Juga
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
