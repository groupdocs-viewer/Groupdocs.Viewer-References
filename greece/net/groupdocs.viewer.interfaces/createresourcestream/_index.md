---
title: "CreateResourceStream"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αντιπροσωπεύει τη μέθοδο που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων του πόρου HTML εξόδου."
type: docs
weight: 720
url: /el/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Αντιπροσωπεύει τη μέθοδο που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων του πόρου HTML εξόδου.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Αριθμός της σελίδας. |
| resource | Πόρος | Πόρος HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |

### Τιμή Επιστροφής

Η ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου του πόρου HTML.

### Δείτε επίσης

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
