---
title: "κλάση Layer"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα στρώμα που περιέχεται στο σχέδιο CAD."
type: docs
url: /el/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Αντιπροσωπεύει ένα στρώμα που περιέχεται στο σχέδιο CAD.

Ο τύπος Layer εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) κλάσης. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Αρχικοποιεί μια νέα παρουσία του Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Αρχικοποιεί μια νέα παρουσία του Layer. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Καθορίζει εάν το τρέχον Layer είναι το ίδιο με το καθορισμένο αντικείμενο Layer. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Ελέγχει εάν το τρέχον [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) είναι ίσο με το καθορισμένο αντικείμενο. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο Layer. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Το όνομα του layer. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Ο δείκτης ορατότητας του layer. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
