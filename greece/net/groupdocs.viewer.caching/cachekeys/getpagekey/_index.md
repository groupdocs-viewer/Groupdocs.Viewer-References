---
title: "GetPageKey"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο σελίδας."
type: docs
weight: 50
url: /el/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο σελίδας.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Ο αριθμός της σελίδας. |
| extension | String | Το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |

### Τιμή Επιστροφής

Μοναδικό αναγνωριστικό για την καταχώρηση στην κρυφή μνήμη που αντιπροσωπεύει το αρχείο σελίδας.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *pageNumber* είναι μικρότερο ή ίσο με το μηδέν. |
| ArgumentException | Εκτοπίζεται όταν το *extension* είναι null ή κενό. |

### Δείτε επίσης

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
