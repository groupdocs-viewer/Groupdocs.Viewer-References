---
title: "create_page_stream μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου σελίδας."
type: docs
url: /el/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου σελίδας.

```python
def create_page_stream(self, page_number):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός μιας σελίδας. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Παράδειγμα

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### Δείτε επίσης
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
