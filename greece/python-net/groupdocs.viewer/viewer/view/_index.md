---
title: "μέθοδος view"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί προβολή όλων των σελίδων του εγγράφου."
type: docs
url: /el/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Δημιουργεί προβολή όλων των σελίδων του εγγράφου.

Μάθετε περισσότερα

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `ViewOptions` | Οι επιλογές προβολής. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `options` είναι None. |
| `PasswordRequiredException` | Όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | Όταν ο καθορισμένος κωδικός πρόσβασης είναι λανθασμένος. |
| `GroupDocsViewerException` | Όταν δεν βρέθηκε κάποιο συνημμένο. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου.

Μάθετε περισσότερα

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `ViewOptions` | Οι επιλογές προβολής. |
| page_numbers | `list[int]` | Οι αριθμοί σελίδων για προβολή. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | όταν `page_numbers` είναι κενό. |
| `PasswordRequiredException` | όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | όταν ο καθορισμένος κωδικός πρόσβασης είναι λανθασμένος. |
| `GroupDocsViewerException` | όταν το συνημμένο δεν μπορεί να βρεθεί. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Δημιουργεί προβολή συγκεκριμένων σελίδων του εγγράφου.

Μάθετε περισσότερα:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `ViewOptions` | Οι επιλογές προβολής. |
| cancellation_token | `CancellationToken` | Διακριτικό ακύρωσης για την ακύρωση της επεξεργασίας. |
| page_numbers | `list[int]` | Οι αριθμοί σελίδων για προβολή. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `page_numbers` είναι κενό. |
| `PasswordRequiredException` | Όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | Όταν ο καθορισμένος κωδικός πρόσβασης είναι λανθασμένος. |
| `GroupDocsViewerException` | όταν το συνημμένο δεν μπορεί να βρεθεί. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Δείτε επίσης
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
