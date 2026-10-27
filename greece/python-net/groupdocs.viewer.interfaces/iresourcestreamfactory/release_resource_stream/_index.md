---
title: "μέθοδος release_resource_stream"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο IResourceStreamFactory.createresourcestream."
type: docs
url: /el/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/).

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός μιας σελίδας. |
| resource | `Resource` | Ο πόρος HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |
| resource_stream | `io.RawIOBase` | Ροή που δημιουργήθηκε από τη μέθοδο `IResourceStreamFactory.create_resource_stream`. |

**Returns:** None.

### Δείτε επίσης
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
