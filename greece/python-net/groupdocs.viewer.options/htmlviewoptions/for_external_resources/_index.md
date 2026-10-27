---
title: "for_external_resources μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο της κλάσης HtmlViewOptions για την απόδοση σε HTML με εξωτερικούς πόρους."
type: docs
url: /el/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Αρχικοποιεί ένα αντικείμενο της κλάσης [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) για την απόδοση σε HTML με εξωτερικούς πόρους.

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί τη stream που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου της σελίδας. |
| create_resource_stream | `CreateResourceStream` | Η μέθοδος που απελευθερώνει τη stream που δημιουργήθηκε από τη μέθοδο `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | Η μέθοδος που δημιουργεί URL για πόρο HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `create_resource_url` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Αρχικοποιεί ένα αντικείμενο της κλάσης HtmlViewOptions για την απόδοση σε HTML με εξωτερικούς πόρους.

Για πρόσθετα παραδείγματα χρήσης, δείτε την τεκμηρίωση του GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Η μέθοδος που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| create_resource_stream | `CreateResourceStream` | Η μέθοδος που δημιουργεί μια stream που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου πόρου HTML. |
| create_resource_url | `CreateResourceUrl` | Η μέθοδος που δημιουργεί URL για έναν πόρο HTML. |
| release_page_stream | `ReleasePageStream` | Η μέθοδος που απελευθερώνει τη stream που δημιουργήθηκε από τον delegate που περάστηκε στο `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Η μέθοδος που απελευθερώνει τη stream που δημιουργήθηκε από τον delegate που περάστηκε στο `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `release_resource_stream` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Φόρτωση φύλλου Excel
    with Viewer("invoice.xlsx") as viewer:
        # Μετατροπή του φύλλου σε HTML με εξωτερικούς πόρους.
        # {0} και {1} αντικαθίστανται με τον τρέχοντα αριθμό σελίδας και το όνομα του πόρου, αντίστοιχα.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Αρχικοποιεί ένα αντικείμενο HtmlViewOptions για την απόδοση σε HTML με εξωτερικούς πόρους.

Για περισσότερες λεπτομέρειες, δείτε την online τεκμηρίωση.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Η factory που υλοποιεί μεθόδους για τη δημιουργία και απελευθέρωση της stream εξόδου σελίδας. |
| resource_stream_factory | `IResourceStreamFactory` | Η factory που υλοποιεί τις απαιτούμενες μεθόδους για τη δημιουργία URL πόρων, την δημιουργία και απελευθέρωση των stream εξόδου πόρων HTML. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `resource_stream_factory` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Δημιουργήστε ένα αρχείο HTML για κάθε σελίδα και αποθηκεύστε τους εξωτερικούς πόρους ξεχωριστά.
    # {0} και {1} αντικαθίστανται με τον τρέχοντα αριθμό σελίδας και το όνομα του πόρου, αντίστοιχα.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Αρχικοποιεί ένα αντικείμενο HtmlViewOptions διαμορφωμένο για τη δημιουργία αρχείων HTML με εξωτερικούς πόρους.

Η παρουσία χρησιμοποιεί τις παρεχόμενες συμβολοσειρές μορφής:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Τα αρχεία εξόδου τοποθετούνται στον τρέχοντα ενεργό φάκελο της εφαρμογής.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Αρχικοποιεί ένα αντικείμενο της κλάσης [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Για το παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path_format | `str` | Η μορφή διαδρομής αρχείου, π.χ. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Η μορφή διαδρομής αρχείου πόρου, π.χ. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Η μορφή URL πόρου, π.χ. `'page_{0}/resource_{1}'`. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `resource_url_format` είναι None ή κενό. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Φορτώστε ένα έγγραφο και αποδώστε κάθε σελίδα σε ένα αρχείο HTML με εξωτερικούς πόρους.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Δείτε επίσης
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
