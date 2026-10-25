---
title: "ReleasePageStream"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt den Stream frei, der durch die mit CreatePageStream./createpagestream verknüpfte Methode instanziiert wurde."
type: docs
weight: 710
url: /de/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

Gibt den Stream frei, der durch die mit [`CreatePageStream`](../createpagestream) verknüpfte Methode instanziiert wurde.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Nummer der Seite. |
| pageStream | Stream | Der Stream, der durch die mit [`CreatePageStream`](../createpagestream) verknüpfte Methode erstellt wurde. |

### Siehe auch

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
