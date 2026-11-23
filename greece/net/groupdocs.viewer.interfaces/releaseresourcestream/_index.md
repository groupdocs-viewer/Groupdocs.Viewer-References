---
title: "ReleaseResourceStream"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με το CreateResourceStream./createresourcestream delegate."
type: docs
weight: 730
url: /el/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με το [`CreateResourceStream`](../createresourcestream) delegate.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Αριθμός της σελίδας. |
| resource | Πόρος | Πόρος HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |
| resourceStream | Stream | Η ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με το [`CreateResourceStream`](../createresourcestream) delegate. |

### Δείτε επίσης

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
