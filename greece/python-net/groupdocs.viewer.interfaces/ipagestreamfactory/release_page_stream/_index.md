---
title: "μέθοδος release_page_stream"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο IPageStreamFactory.createpagestream."
type: docs
url: /el/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/).

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός μιας σελίδας. |
| page_stream | `io.RawIOBase` | Ροή που δημιουργήθηκε από τη μέθοδο `IPageStreamFactory.create_page_stream`. |

### Δείτε επίσης
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
