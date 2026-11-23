---
title: "IPageStreamFactory"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit les méthodes requises pour instancier et libérer le flux de la page de sortie."
type: docs
weight: 760
url: /fr/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

Définit les méthodes requises pour instancier et libérer le flux de la page de sortie.

```csharp
public interface IPageStreamFactory
```

## Méthodes

| Nom | Description |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | Crée le flux utilisé pour écrire les données de page de sortie. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | Libère le flux créé par la méthode [`CreatePageStream`](./createpagestream). |

### Voir aussi

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
