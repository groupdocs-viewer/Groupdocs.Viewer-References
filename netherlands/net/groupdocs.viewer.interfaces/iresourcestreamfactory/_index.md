---
title: IResourceStreamFactory
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Definieert de methoden die nodig zijn voor het maken van een bronURL het instantiëren en vrijgeven van uitvoer HTMLbronstroom.
type: docs
weight: 180
url: /nl/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---
## IResourceStreamFactory interface

Definieert de methoden die nodig zijn voor het maken van een bron-URL, het instantiëren en vrijgeven van uitvoer HTML-bronstroom.

```csharp
public interface IResourceStreamFactory
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Creëert de stream die wordt gebruikt om HTML-resourcegegevens te schrijven. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Maakt de URL voor HTML-bron. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Geeft de stream vrij die is gemaakt door[`CreateResourceStream`](./createresourcestream) methode. |

### Zie ook

* naamruimte [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->