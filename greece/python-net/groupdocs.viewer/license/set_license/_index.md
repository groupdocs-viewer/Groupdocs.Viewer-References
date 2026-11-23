---
title: "μέθοδος set_license"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Εφαρμόστε μια άδεια στην τρέχουσα διαδικασία."
type: docs
url: /el/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Εφαρμόστε μια άδεια στην τρέχουσα διαδικασία.

```python
def set_license(self, license_source):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| license_source |  | Είτε μια διαδρομή συμβολοσειράς προς ένα αρχείο ``.lic`` είτε ένα αναγνώσιμο αντικείμενο τύπου αρχείου που παρέχει τα byte της άδειας. Τα εισερχόμενα τύπου αρχείου γράφονται σε ένα προσωρινό αρχείο πριν περάσουν στη γέφυρα. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `TypeError` | Αν το ``license_source`` δεν είναι ούτε διαδρομή συμβολοσειράς ούτε αναγνώσιμο αντικείμενο τύπου αρχείου. |

### Δείτε επίσης
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
