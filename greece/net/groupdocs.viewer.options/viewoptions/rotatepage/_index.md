---
title: "RotatePage"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Εφαρμόζει τη δεξιόστροφη περιστροφή σε μια σελίδα."
type: docs
weight: 30
url: /el/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Εφαρμόζει τη δεξιόστροφη περιστροφή σε μια σελίδα.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Ο αριθμός σελίδας, πρέπει να είναι αυστηρά μεγαλύτερος από 0. |
| περιστροφή | Περιστροφή | Η τιμή περιστροφής. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | Εκτοπίζεται όταν το *pageNumber* είναι μικρότερο ή ίσο με το μηδέν. |
| ArgumentException | Εκτοπίζεται όταν η περιστροφή για τη σελίδα με αριθμό *pageNumber* έχει ήδη προστεθεί. |

### Παρατηρήσεις

Για λεπτομέρειες, δείτε την [τεκμηρίωση](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### Δείτε επίσης

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
