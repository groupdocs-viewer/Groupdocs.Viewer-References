---
title: "create_resource_stream μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου πόρου HTML."
type: docs
url: /el/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου πόρου HTML.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός μιας σελίδας. |
| resource | `Resource` | Ο πόρος HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Δημιουργήστε μια ροή για έναν πόρο CSS στη σελίδα 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### Δείτε επίσης
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
