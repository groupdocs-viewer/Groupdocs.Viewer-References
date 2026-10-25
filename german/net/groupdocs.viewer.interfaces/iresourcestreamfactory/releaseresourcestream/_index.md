---
title: "ReleaseResourceStream"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt den von CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream Methode erstellten Stream frei."
type: docs
weight: 30
url: /de/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

Gibt den von [`CreateResourceStream`](../createresourcestream) Methode erstellten Stream frei.

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer einer Seite. |
| Ressource | Resource | Die HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |
| resourceStream | Stream | Von [`CreateResourceStream`](../createresourcestream) Methode erstellter Stream. |

### Siehe auch

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
