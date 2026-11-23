---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του Word."
type: docs
url: /el/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Αρχικοποιεί μια νέα παρουσία του [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| word | `str` | Η λέξη. |
| x | `float` | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
| y | `float` | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
| width | `float` | Το πλάτος του ορθογωνίου που περιέχει τη λέξη. |
| height | `float` | Το ύψος του ορθογωνίου που περιέχει τη λέξη. |
| characters | `List[Character]` | Οι χαρακτήρες που περιέχονται στη λέξη. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `characters` είναι null. |

### Δείτε επίσης
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
