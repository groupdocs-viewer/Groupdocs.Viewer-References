---
title: "μέθοδος from_html_view_options"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα στιγμιότυπο της κλάσης ViewInfoOptions βασισμένο στο αντικείμενο HtmlViewOptions."
type: docs
url: /el/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης ViewInfoOptions βασισμένο στο αντικείμενο HtmlViewOptions.

```python
def from_html_view_options(cls, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `HtmlViewOptions` | Οι επιλογές προβολής HTML. |

**Returns:** A new ViewInfoOptions instance.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν `options` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### Δείτε επίσης
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
