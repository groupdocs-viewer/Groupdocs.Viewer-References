---
title: "Κλάση LoadOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Οι επιλογές που χρησιμοποιούνται για το άνοιγμα ενός αρχείου."
type: docs
url: /el/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Οι επιλογές που χρησιμοποιούνται για το άνοιγμα ενός αρχείου.

Ο τύπος LoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Αρχικοποιεί μια παρουσία της κλάσης [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Αρχικοποιεί μια νέα παρουσία του LoadOptions. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Η ιδιότητα ενεργοποιεί την ανίχνευση κωδικοποίησης για αρχεία [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), και [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | Η κωδικοποίηση που χρησιμοποιείται κατά το άνοιγμα αρχείων κειμένου ή μηνυμάτων ηλεκτρονικού ταχυδρομείου όπως [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), και [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Η προεπιλεγμένη τιμή είναι `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Ο τύπος του αρχείου προς άνοιγμα. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα κρυπτογραφημένου αρχείου. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Το χρονικό όριο για τη φόρτωση εξωτερικών πόρων. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Η ιδιότητα απενεργοποιεί τη φόρτωση όλων των εξωτερικών πόρων όπως εικόνες, εκτός από εκείνους που αναφέρονται στο [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Η ιδιότητα επιτρέπει στο GroupDocs.Viewer να προσπαθήσει να επισκευάσει τη δομική αλλοίωση σε έγγραφα PDF. Η προεπιλογή είναι False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | Η λίστα των τμημάτων URL που αντιστοιχούν σε εξωτερικούς πόρους που πρέπει να φορτωθούν όταν [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) ορίζεται σε `True`. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
