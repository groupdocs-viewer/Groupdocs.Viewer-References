---
title: "μέθοδος for_html_view"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα στιγμιότυπο ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε HTML."
type: docs
url: /el/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Αρχικοποιεί ένα στιγμιότυπο ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Παράδειγμα

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Δημιουργήστε επιλογές πληροφοριών προβολής για μορφή HTML (μονή σελίδα)
    options = ViewInfoOptions.for_html_view(True)

    # Φορτώστε ένα έγγραφο και ανακτήστε πληροφορίες προβολής
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Αρχικοποιεί ένα στιγμιότυπο ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| render_single_page | `bool` | Ενεργοποιεί την απόδοση περιεχομένου HTML σε μια μονή σελίδα. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Ανακτήστε πληροφορίες προβολής για HTML με μία μόνο σελίδα
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Δείτε επίσης
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
