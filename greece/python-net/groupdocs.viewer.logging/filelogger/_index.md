---
title: "FileLogger κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Γράφει μηνύματα καταγραφής στο αρχείο."
type: docs
url: /el/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

Γράφει μηνύματα καταγραφής στο αρχείο.

Ο τύπος FileLogger εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | Αρχικοποιεί έναν καταγραφέα που γράφει μηνύματα σε αρχείο. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | Γράφει ένα μήνυμα σφάλματος στην κονσόλα. Τα μηνύματα καταγραφής σφαλμάτων παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | Γράφει ένα μήνυμα εντοπισμού στην καταγραφή. Τα μηνύματα καταγραφής εντοπισμού παρέχουν γενικά χρήσιμες πληροφορίες για τη ροή της εφαρμογής. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | Γράφει ένα μήνυμα προειδοποίησης στην κονσόλα. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
