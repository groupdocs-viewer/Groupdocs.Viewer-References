---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης Page."
type: docs
url: /el/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο του [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

Αρχικοποιεί ένα νέο [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) αντικείμενο.

```python
def __init__(self, number, visible):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `number` είναι μικρότερο ή ίσο με το μηδέν. |

## __init__ {#number-name-visible}

Αρχικοποιεί ένα νέο αντικείμενο Page.

```python
def __init__(self, number, name, visible):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| name | `str` | Το όνομα του φύλλου εργασίας ή της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `number` είναι μικρότερο ή ίσο με το μηδέν. |

## __init__ {#number-visible-width-height}

Αρχικοποιεί ένα νέο [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) αντικείμενο.

```python
def __init__(self, number, visible, width, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |
| width | `int` | Το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| height | `int` | Το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `height` είναι μικρότερο ή ίσο με το μηδέν. |

## __init__ {#number-name-visible-width-height}

Αρχικοποιεί ένα νέο αντικείμενο του [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| name | `str` | Το όνομα του φύλλου εργασίας ή της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |
| width | `int` | Το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| height | `int` | Το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `height` είναι μικρότερο ή ίσο με το μηδέν. |

## __init__ {#number-visible-width-height-lines}

Αρχικοποιεί ένα νέο αντικείμενο του [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |
| width | `int` | Το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| height | `int` | Το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| lines | `List[Line]` | Οι γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργή εξαγωγή κειμένου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `lines` είναι None. |

## __init__ {#number-name-visible-width-height-lines}

Αρχικοποιεί ένα νέο αντικείμενο του [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| number | `int` | Ο αριθμός της σελίδας. |
| name | `str` | Το όνομα του φύλλου εργασίας ή της σελίδας. |
| visible | `bool` | Ο δείκτης ορατότητας της σελίδας. |
| width | `int` | Το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| height | `int` | Το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| lines | `List[Line]` | Οι γραμμές που περιέχονται στη σελίδα όταν προβάλλεται ως JPG ή PNG με ενεργή εξαγωγή κειμένου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `lines` είναι None. |

### Δείτε επίσης
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
