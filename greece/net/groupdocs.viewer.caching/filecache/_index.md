---
title: "FileCache"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αντιπροσωπεύει μια τοπική cache στον δίσκο."
type: docs
weight: 990
url: /el/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Αντιπροσωπεύει μια τοπική κρυφή μνήμη στον δίσκο.

```csharp
public class FileCache : ICache
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Δημιουργεί νέα παρουσία της κλάσης [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | Δημιουργεί νέα παρουσία της κλάσης [`FileCache`](../filecache). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | Η σχετική ή απόλυτη διαδρομή προς το φάκελο cache. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | Ο υποφάκελος που θα προσαρτηθεί στο [`CachePath`](./cachepath). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Επιστρέφει όλα τα ονόματα αρχείων που περιέχουν το φίλτρο στο όνομα αρχείου. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Σειριοποιεί δεδομένα στον τοπικό δίσκο. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Αποσειριοποιεί δεδομένα που σχετίζονται με αυτό το κλειδί, εάν υπάρχουν. |

### Δείτε επίσης

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
