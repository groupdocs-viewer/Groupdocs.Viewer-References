---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του FileCache."
type: docs
url: /el/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Αρχικοποιεί μια νέα παρουσία του FileCache.

```python
def __init__(self, cache_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cache_path | `str` | Σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η προσωρινή μνήμη εγγράφου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `cache_path` είναι None. |

## __init__ {#cache_path-cache_sub_folder}

Αρχικοποιεί μια νέα παρουσία της κλάσης FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cache_path | `str` | Σχετική ή απόλυτη διαδρομή όπου θα αποθηκευτεί η προσωρινή μνήμη εγγράφου. |
| cache_sub_folder | `str` | Ο υποφάκελος που θα προσαρτηθεί στο `cache_path`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `cache_sub_folder` είναι None. |

### Δείτε επίσης
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
