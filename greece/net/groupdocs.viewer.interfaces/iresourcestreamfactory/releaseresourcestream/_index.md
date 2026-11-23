---
title: "ReleaseResourceStream"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream."
type: docs
weight: 30
url: /el/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

Απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο [`CreateResourceStream`](../createresourcestream).

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Παράμετρος | Type | Περιγραφή |
| --- | --- | --- |
| pageNumber | Int32 | Ο αριθμός μιας σελίδας. |
| resource | Πόρος | Ο πόρος HTML όπως γραμματοσειρά, στυλ, εικόνα ή γραφικά. |
| resourceStream | Stream | Ροή που δημιουργήθηκε από τη μέθοδο [`CreateResourceStream`](../createresourcestream). |

### Δείτε επίσης

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
