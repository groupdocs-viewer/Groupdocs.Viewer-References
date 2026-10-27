---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του Attachment."
type: docs
url: /el/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Αρχικοποιεί μια νέα παρουσία του Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | `str` | Όνομα αρχείου συνημμένου. |
| file_path | `str` | Σχετική διαδρομή συνημμένου π.χ. "folder/file.docx" ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `file_path` είναι None ή κενό. |

## __init__ {#id-file_name-file_path-size}

Αρχικοποιεί μια νέα παρουσία της κλάσης Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| id | `str` | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |
| file_name | `str` | Όνομα αρχείου συνημμένου. |
| file_path | `str` | Σχετική διαδρομή συνημμένου π.χ. `folder/file.docx` ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |
| size | `int` | Μέγεθος αρχείου συνημμένου σε bytes. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `file_path` είναι null ή κενό. |

## __init__ {#id-file_name-file_path-file_type-size}

Αρχικοποιεί μια νέα παρουσία της κλάσης Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| id | `str` | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |
| file_name | `str` | Όνομα αρχείου συνημμένου. |
| file_path | `str` | Σχετική διαδρομή συνημμένου π.χ. `folder/file.docx` ή όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε μήνυμα ηλεκτρονικού ταχυδρομείου ή αρχείο δεδομένων. |
| file_type | `FileType` | Τύπος αρχείου συνημμένου. |
| size | `int` | Μέγεθος αρχείου συνημμένου σε bytes. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `file_type` είναι null. |

### Δείτε επίσης
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
