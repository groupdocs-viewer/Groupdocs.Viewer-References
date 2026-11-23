---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της κλάσης Watermark."
type: docs
url: /el/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/).

```python
def __init__(self, text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | `str` | Κείμενο υδατογραφήματος. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `text` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

with Viewer("sample.docx") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "add_text_watermark/output-watermark.html"
    )
    view_options.watermark = Watermark("This is a watermark")
    viewer.view(view_options)
```

### Δείτε επίσης
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
