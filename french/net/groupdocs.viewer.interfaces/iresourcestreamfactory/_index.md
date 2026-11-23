---
title: "IResourceStreamFactory"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit les méthodes requises pour créer l'URL de ressource, instancier et libérer le flux de ressource HTML de sortie."
type: docs
weight: 770
url: /fr/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Définit les méthodes requises pour créer l'URL de la ressource, instancier et libérer le flux de la ressource HTML de sortie.

```csharp
public interface IResourceStreamFactory
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Crée le flux utilisé pour écrire les données de ressource HTML de sortie. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Crée l'URL pour la ressource HTML. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Libère le flux créé par la méthode [`CreateResourceStream`](./createresourcestream). |

### Voir aussi

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
