---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer för .NET API-referens
description: Frigör strömmen skapad avCreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream metod.
type: docs
weight: 30
url: /sv/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---
## IResourceStreamFactory.ReleaseResourceStream method

Frigör strömmen skapad av[`CreateResourceStream`](../createresourcestream) metod.

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | Int32 | Numret på en sida. |
| resource | Resource | HTML-resursen som typsnitt, stil, bild eller grafik. |
| resourceStream | Stream | Stream skapad av[`CreateResourceStream`](../createresourcestream) metod. |

### Se även

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namnutrymme [GroupDocs.Viewer.Interfaces](../../iresourcestreamfactory)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->