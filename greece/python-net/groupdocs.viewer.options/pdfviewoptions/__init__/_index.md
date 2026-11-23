---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία του PdfViewOptions."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Αρχικοποιεί ένα στιγμιότυπο του [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου αρχείου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `create_file_stream` είναι `None`. |

## __init__ {#create_file_stream-release_file_stream}

Αρχικοποιεί ένα νέο στιγμιότυπο PdfViewOptions.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Κλήση που επιστρέφει μια ροή `io.RawIOBase` που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου αρχείου. |
| release_file_stream | `ReleaseFileStream` | Κλήση που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που έχει εκχωρηθεί στο `create_file_stream`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `release_file_stream` είναι None. |

## __init__ {#file_stream_factory}

Αρχικοποιεί ένα στιγμιότυπο PdfViewOptions.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Το εργοστάσιο που υλοποιεί μεθόδους για τη δημιουργία και την απελευθέρωση της ροής εξόδου αρχείου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `file_stream_factory` είναι None. |

## __init__

Αρχικοποιεί ένα στιγμιότυπο PdfViewOptions.

Αυτός ο κατασκευαστής αρχικοποιεί ένα PdfViewOptions με `\"output.pdf\"` ως μορφή διαδρομής αρχείου για το αρχείο εξόδου. Το αρχείο εξόδου θα τοποθετηθεί στον τρέχοντα κατάλογο εργασίας της εφαρμογής.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, output_file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_file_path | `str` | Η διαδρομή για το αρχείο PDF εξόδου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `output_file_path` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Δείτε επίσης
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
