---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα στιγμιότυπο της κλάσης JpgViewOptions."
type: docs
url: /el/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης JpgViewOptions.

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

Αρχικοποιεί ένα στιγμιότυπο της κλάσης JpgViewOptions.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Κλήσιμο που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| release_page_stream | `ReleasePageStream` | Κλήσιμο που απελευθερώνει μια ροή που δημιουργήθηκε από τη μέθοδο που έχει εκχωρηθεί στον αντιπρόσωπο που περάστηκε στο `create_page_stream`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `release_page_stream` είναι None. |

## __init__ {#page_stream_factory}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση στο https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Το factory που υλοποιεί μεθόδους για τη δημιουργία και απελευθέρωση της ροής εξόδου σελίδας. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `page_stream_factory` είναι None. |

## __init__

Αρχικοποιεί ένα στιγμιότυπο JpgViewOptions.

Αυτός ο κατασκευαστής αρχικοποιεί μια παρουσία του [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) με το `"p_{0}.jpg"` ως μορφή διαδρομής αρχείου για τα εξαγόμενα αρχεία. Τα εξαγόμενα αρχεία τοποθετούνται στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

Αρχικοποιεί ένα νέο στιγμιότυπο του [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, file_path_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path_format | `str` | Η μορφή διαδρομής αρχείου, π.χ. `'page_{0}.jpg'`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `file_path_format` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Φορτώστε ένα έγγραφο (π.χ., ένα αρχείο Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Δημιουργήστε επιλογές προβολής JPEG με ένα μοτίβο ονόματος αρχείου.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Δείτε επίσης
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
