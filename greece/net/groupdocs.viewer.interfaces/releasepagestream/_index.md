---
title: "ReleasePageStream"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με CreatePageStream./createpagestream delegate."
type: docs
weight: 710
url: /el/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με [`CreatePageStream`](../createpagestream) delegate.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Αριθμός της σελίδας. |
| pageStream | Stream | Η ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με [`CreatePageStream`](../createpagestream) delegate. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
