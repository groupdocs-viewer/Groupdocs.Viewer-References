---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Geeft de stream vrij die is gemaakt doorCreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream methode.
type: docs
weight: 30
url: /nl/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---
## IResourceStreamFactory.ReleaseResourceStream method

Geeft de stream vrij die is gemaakt door[`CreateResourceStream`](../createresourcestream) methode.

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | Int32 | Het nummer van een pagina. |
| resource | Resource | De HTML-bron zoals lettertype, stijl, afbeelding of afbeeldingen. |
| resourceStream | Stream | Stroom gemaakt door[`CreateResourceStream`](../createresourcestream) methode. |

### Zie ook

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* naamruimte [GroupDocs.Viewer.Interfaces](../../iresourcestreamfactory)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->