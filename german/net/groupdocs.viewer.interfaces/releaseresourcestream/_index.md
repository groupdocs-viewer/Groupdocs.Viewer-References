---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt den Stream frei, der durch die mit CreateResourceStream./createresourcestream verknüpfte Methode instanziiert wurde."
type: docs
weight: 730
url: /de/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

Gibt den Stream frei, der durch die mit [`CreateResourceStream`](../createresourcestream) verknüpfte Methode instanziiert wurde.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Nummer der Seite. |
| Ressource | Resource | HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |
| resourceStream | Stream | Der Stream, der von der mit [`CreateResourceStream`](../createresourcestream) verknüpften Methode erstellt wurde. |

### Siehe auch

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
