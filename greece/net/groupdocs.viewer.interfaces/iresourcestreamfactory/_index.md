---
title: "IResourceStreamFactory"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Ορίζει τις μεθόδους που απαιτούνται για τη δημιουργία URL πόρου, την δημιουργία και την απελευθέρωση της ροής εξόδου HTML πόρου."
type: docs
weight: 770
url: /el/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Ορίζει τις μεθόδους που απαιτούνται για τη δημιουργία του URL πόρου, τη δημιουργία και την απελευθέρωση της ροής πόρου HTML εξόδου.

```csharp
public interface IResourceStreamFactory
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων εξόδου του πόρου HTML. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Δημιουργεί το URL για τον πόρο HTML. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο [`CreateResourceStream`](./createresourcestream). |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
