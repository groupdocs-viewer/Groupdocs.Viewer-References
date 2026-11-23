---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings."
type: docs
url: /el/python-net/groupdocs.viewer/viewersettings/__init__/
is_root: false
weight: 10
---


## __init__ {#cache-logger}

Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings.

```python
def __init__(self, cache, logger):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cache | `ICache` | Η κρυφή μνήμη. |
| logger | `ILogger` | Ο logger. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `cache` είναι None. |

### Παράδειγμα

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

Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings.

```python
def __init__(self, cache):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cache | `ICache` | Η κρυφή μνήμη. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `cache` είναι None. |

## __init__ {#logger}

Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings.

```python
def __init__(self, logger):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| logger | `ILogger` | Ο logger. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `logger` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Δείτε επίσης
* class [`ViewerSettings`](/viewer/python-net/groupdocs.viewer/viewersettings/)
