---
title: "ViewerSettings κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του Viewer."
type: docs
url: /el/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Ο τύπος ViewerSettings εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Αρχικοποιεί ένα νέο αντικείμενο ViewerSettings. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Η υλοποίηση cache που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων απόδοσης. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Η υλοποίηση logger που χρησιμοποιείται για την καταγραφή (Σφάλματα, Προειδοποιήσεις, Ιχνηλάσεις). |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
