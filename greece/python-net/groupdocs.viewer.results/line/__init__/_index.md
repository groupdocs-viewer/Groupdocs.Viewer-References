---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του Line."
type: docs
url: /el/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Αρχικοποιεί μια νέα παρουσία του [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) κλάσης.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| line | `str` | Η γραμμή. |
| x | `float` | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη γραμμή. |
| y | `float` | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη γραμμή. |
| width | `float` | Το πλάτος του ορθογωνίου που περιέχει τη γραμμή (σε pixel). |
| height | `float` | Το ύψος του ορθογωνίου που περιέχει τη γραμμή (σε pixel). |
| words | `List[Word]` | Οι λέξεις που περιέχονται στη γραμμή. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `line` είναι null ή κενό, ή όταν το `words` είναι null. |

### Δείτε επίσης
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
