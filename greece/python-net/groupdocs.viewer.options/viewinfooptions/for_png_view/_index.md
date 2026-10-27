---
title: "for_png_view μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα στιγμιότυπο της κλάσης ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PNG."
type: docs
url: /el/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Δημιουργήστε επιλογές πληροφοριών προβολής για μορφή PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Φορτώστε ένα έγγραφο και λάβετε πληροφορίες προβολής για PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extract_text | `bool` | Ενεργοποιεί την εξαγωγή κειμένου. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Παράδειγμα

```python
from groupdocs.viewer.options import ViewInfoOptions

# Δημιουργήστε επιλογές πληροφοριών προβολής για μορφή PNG με ενεργοποιημένη εξαγωγή κειμένου
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Δείτε επίσης
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
