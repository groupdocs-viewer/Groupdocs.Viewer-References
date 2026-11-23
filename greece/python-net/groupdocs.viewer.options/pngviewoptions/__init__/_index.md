---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο PngViewOptions."
type: docs
url: /el/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Αρχικοποιεί ένα νέο [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) αντίγραφο.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, create_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `create_page_stream` είναι None. |

## __init__ {#create_page_stream-release_page_stream}

Αρχικοποιεί ένα αντίγραφο της κλάσης [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| release_page_stream | `ReleasePageStream` | Η μέθοδος που απελευθερώνει ένα ρεύμα που δημιουργήθηκε από τη μέθοδο που έχει εκχωρηθεί στον αντιπρόσωπο που περάστηκε ως παράμετρος στο `create_page_stream`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `release_page_stream` είναι None. |

## __init__ {#page_stream_factory}

Αρχικοποιεί ένα νέο [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) αντίγραφο.

Για περισσότερες πληροφορίες, δείτε την τεκμηρίωση.

```python
def __init__(self, page_stream_factory):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Το factory που υλοποιεί μεθόδους για τη δημιουργία και απελευθέρωση της ροής εξόδου σελίδας. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `page_stream_factory` είναι `None`. |

## __init__

Αρχικοποιεί ένα αντίγραφο PngViewOptions.

Αυτός ο κατασκευαστής δημιουργεί ένα [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) με το ``\"p_{0}.png\"`` ως προεπιλεγμένη μορφή διαδρομής αρχείου για τα εξαγόμενα αρχεία. Τα παραγόμενα αρχεία PNG αποθηκεύονται στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Αρχικοποιεί ένα νέο [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) αντίγραφο.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, file_path_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path_format | `str` | Η μορφή διαδρομής αρχείου, π.χ. `'page_{0}.png'`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `file_path_format` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Δείτε επίσης
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
