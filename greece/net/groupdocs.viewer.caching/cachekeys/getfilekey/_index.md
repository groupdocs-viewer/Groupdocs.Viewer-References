---
title: "GetFileKey"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο."
type: docs
weight: 40
url: /el/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο.

```csharp
public static string GetFileKey(string extension)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| extension | String | Το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |

### Τιμή Επιστροφής

Μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *extension* είναι null ή κενό. |

### Δείτε επίσης

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
