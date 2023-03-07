---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer για Αναφορά API .NET
description: Κυκλοφορεί ροή η οποία δημιουργήθηκε με τη μέθοδο που σχετίζεται μεCreateResourceStream./createresourcestream εκπρόσωπος.
type: docs
weight: 210
url: /el/net/groupdocs.viewer.interfaces/releaseresourcestream/
---
## ReleaseResourceStream delegate

Κυκλοφορεί ροή η οποία δημιουργήθηκε με τη μέθοδο που σχετίζεται με[`CreateResourceStream`](../createresourcestream) εκπρόσωπος.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Αριθμός σελίδας. |
| resource | Resource | Πόροι HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |
| resourceStream | Stream | Η ροή που δημιουργήθηκε με τη μέθοδο που σχετίζεται με[`CreateResourceStream`](../createresourcestream) αντιπρόσωπος. |

### Δείτε επίσης

* class [Resource](../../groupdocs.viewer.results/resource)
* χώρος ονομάτων [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* συνέλευση [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->