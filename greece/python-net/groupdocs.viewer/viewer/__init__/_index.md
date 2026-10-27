---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer."
type: docs
url: /el/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Μάθετε περισσότερα

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Η μέθοδος που επιστρέφει ένα αναγνώσιμο ρεύμα. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `get_file_stream` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

Αρχικοποιεί μια νέα παρουσία της [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Η μέθοδος που επιστρέφει ένα αναγνώσιμο ρεύμα. |
| get_load_options | `Func[LoadOptions]` | Η μέθοδος που επιστρέφει τις επιλογές φόρτωσης εγγράφου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εκτοξεύεται όταν το `get_load_options` είναι None. |
| `Remarks` | - Περισσότερα για τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - Περισσότερα για τις δυνατότητες του GroupDocs.Viewer για .NET: https://docs.groupdocs.com/display/viewernet/Developer+Guide - Περισσότερα για τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: https://docs.groupdocs.com/display/viewernet/Loading |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

Αρχικοποιεί μια νέα παρουσία του [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Η μέθοδος που επιστρέφει ένα αναγνώσιμο ρεύμα. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

Αρχικοποιεί μια νέα παρουσία Viewer.

Περισσότερες πληροφορίες:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | Κλήσιμο που επιστρέφει ένα αναγνώσιμο ρεύμα. |
| get_load_options | `Func[LoadOptions]` | Κλήσιμο που επιστρέφει τις επιλογές φόρτωσης εγγράφου. |
| settings | `ViewerSettings` | Ρυθμίσεις Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `stream` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

Αρχικοποιεί μια νέα παρουσία Viewer.

Μάθετε περισσότερα:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| leave_open | `bool` | True για να αφήσετε το ρεύμα ανοιχτό μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, False. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `stream` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

Αρχικοποιεί μια νέα παρουσία της [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Μάθετε περισσότερα:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης εγγράφου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν `load_options` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

Αρχικοποιεί μια νέα παρουσία Viewer.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης εγγράφου. |
| leave_open | `bool` | True για να αφήσετε το ρεύμα ανοιχτό μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, False. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν `load_options` είναι None. |
| `Remarks` | - Περισσότερα για τους τύπους αρχείων που υποστηρίζει το GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - Περισσότερα για τις δυνατότητες του GroupDocs.Viewer για .NET: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - Περισσότερα για τη φόρτωση κρυπτογραφημένων εγγράφων και την προβολή αρχείων από αποθηκευτικούς χώρους τρίτων με το GroupDocs.Viewer για .NET: <https://docs.groupdocs.com/display/viewernet/Loading> |

### Παράδειγμα

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

Αρχικοποιεί μια νέα παρουσία Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

Αρχικοποιεί μια νέα παρουσία Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |
| leave_open | `bool` | True για να αφήσετε το ρεύμα ανοιχτό μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, False. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

Αρχικοποιεί μια νέα παρουσία Viewer.

Ο κατασκευαστής απαιτεί ένα ρεύμα αρχείου (`io.RawIOBase`) και προαιρετικά δέχεται επιλογές φόρτωσης εγγράφου και ρυθμίσεις Viewer.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης εγγράφου. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `stream`, το `load_options` ή το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

# Ανοίξτε ένα αρχείο ως δυαδικό ρεύμα και δημιουργήστε ένα Viewer
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Χρησιμοποιήστε το viewer, π.χ., αποδώστε σε HTML
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

Αρχικοποιεί μια νέα παρουσία της [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Μάθετε περισσότερα:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| load_options | `LoadOptions` | Οι επιλογές φόρτωσης εγγράφου. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |
| leave_open | `bool` | True για να αφήσετε το ρεύμα ανοιχτό μετά την καταστροφή του αντικειμένου Viewer· διαφορετικά, False. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή προς το αρχείο που θα αποδοθεί. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `file_path` είναι `None` ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

# Αρχικοποιήστε το viewer με μια διαδρομή εγγράφου
with Viewer("./sample.docx") as viewer:
    # Το viewer είναι έτοιμο να αποδώσει το έγγραφο
    pass
```

## __init__ {#file_path-settings}

Αρχικοποιεί νέα παρουσία της κλάσης [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Μάθετε περισσότερα:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `settings` είναι null. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

Αρχικοποιεί μια νέα παρουσία της [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
| load_options | `LoadOptions` | Οι επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `load_options` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

Αρχικοποιεί μια νέα παρουσία Viewer.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | `str` | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
| load_options | `LoadOptions` | Οι επιλογές που χρησιμοποιούνται για το άνοιγμα του αρχείου. |
| settings | `ViewerSettings` | Οι ρυθμίσεις του Viewer. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `settings` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Δείτε επίσης
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
