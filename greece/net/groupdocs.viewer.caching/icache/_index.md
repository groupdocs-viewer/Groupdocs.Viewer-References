---
title: "ICache"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ορίζει τις μεθόδους που απαιτούνται για την αποθήκευση του αποδομένου εγγράφου και των πόρων του εγγράφου στην κρυφή μνήμη."
type: docs
weight: 1000
url: /el/net/groupdocs.viewer.caching/icache/
---

## ICache interface

Ορίζει τις μεθόδους που απαιτούνται για την αποθήκευση του αποδομένου εγγράφου και των πόρων του εγγράφου στην κρυφή μνήμη.

```csharp
public interface ICache
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Επιστρέφει όλα τα κλειδιά που ταιριάζουν με το φίλτρο. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Εισάγει μια καταχώρηση cache στην cache. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Αποκτά την καταχώρηση που σχετίζεται με αυτό το κλειδί, εάν υπάρχει. |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
