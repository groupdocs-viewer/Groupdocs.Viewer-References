---
title: "error μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Γράφει ένα μήνυμα σφάλματος."
type: docs
url: /el/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Γράφει ένα μήνυμα σφάλματος.

Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

```python
def error(self, message, exception):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| message | `str` | Το μήνυμα σφάλματος. |
| exception | `Exception` | Η εξαίρεση. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν `exception` είναι None. |

### Δείτε επίσης
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
