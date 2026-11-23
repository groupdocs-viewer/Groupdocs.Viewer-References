---
title: "GetResourceKey"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση στην κρυφή μνήμη που αντιπροσωπεύει το αντικείμενο Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 70
url: /el/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση στην κρυφή μνήμη που αντιπροσωπεύει το αντικείμενο [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Ο αριθμός της σελίδας. |
| resource | Πόρος | Ο πόρος HTML. |

### Τιμή Επιστροφής

Μοναδικό αναγνωριστικό για την καταχώρηση στην κρυφή μνήμη που αντιπροσωπεύει το αντικείμενο [`Resource`](../../../groupdocs.viewer.results/resource).

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *pageNumber* είναι μικρότερο ή ίσο με το μηδέν. |
| ArgumentNullException | Εκτοπίζεται όταν το *resource* είναι null. |

### Δείτε επίσης

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
