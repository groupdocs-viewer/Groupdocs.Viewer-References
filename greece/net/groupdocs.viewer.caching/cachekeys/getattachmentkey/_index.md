---
title: "GetAttachmentKey"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο συνημμένου."
type: docs
weight: 10
url: /el/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο συνημμένου.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| attachmentId | String | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |

### Τιμή Επιστροφής

Μοναδικό αναγνωριστικό για την καταχώρηση στην κρυφή μνήμη που αντιπροσωπεύει το αρχείο συνημμένου.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εκτοπίζεται όταν το *attachmentId* είναι null ή κενό. |

### Δείτε επίσης

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
