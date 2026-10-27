---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης Layer."
type: docs
url: /el/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) κλάσης.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer.results import Layer

# Δημιουργήστε ένα στρώμα με το καθορισμένο όνομα.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Αρχικοποιεί μια νέα παρουσία του Layer.

```python
def __init__(self, name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Το όνομα του layer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `name` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer.results import Layer

# Δημιουργήστε ένα στρώμα με το καθορισμένο όνομα
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Αρχικοποιεί μια νέα παρουσία του Layer.

```python
def __init__(self, name, visible):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | `str` | Το όνομα του layer. |
| visible | `bool` | Ο δείκτης ορατότητας του layer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `name` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Δείτε επίσης
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
