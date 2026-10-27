---
title: "μέθοδος for_embedded_resources"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο HtmlViewOptions για την απόδοση HTML με ενσωματωμένους πόρους."
type: docs
url: /el/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Αρχικοποιεί ένα αντικείμενο HtmlViewOptions για την απόδοση HTML με ενσωματωμένους πόρους.

Για περισσότερες λεπτομέρειες, δείτε την τεκμηρίωση.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `create_page_stream` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Αρχικοποιεί ένα αντικείμενο της κλάσης [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) για την απόδοση σε HTML με ενσωματωμένους πόρους.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| release_page_stream | `ReleasePageStream` | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που έχει ανατεθεί στην παράμετρο `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `release_page_stream` είναι `None`. Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση. |

## for_embedded_resources {#page_stream_factory}

Αρχικοποιεί ένα αντικείμενο HtmlViewOptions για την απόδοση σε HTML με ενσωματωμένους πόρους.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Το factory που υλοποιεί μεθόδους για τη δημιουργία και απελευθέρωση της ροής εξόδου σελίδας. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το page_stream_factory είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Αρχικοποιεί ένα αντικείμενο της κλάσης [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) με ενσωματωμένους πόρους.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_embedded_resources(cls):
    ...
```

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Αρχικοποιεί ένα αντικείμενο HtmlViewOptions για ενσωματωμένους πόρους.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path_format | `str` | Η μορφή διαδρομής αρχείου π.χ. 'page_{0}.html'. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `file_path_format` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Δείτε επίσης
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
