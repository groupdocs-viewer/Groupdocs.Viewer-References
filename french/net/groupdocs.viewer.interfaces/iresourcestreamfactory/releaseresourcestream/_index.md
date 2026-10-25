---
title: "ReleaseResourceStream"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Libère le flux créé par la méthode CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream."
type: docs
weight: 30
url: /fr/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

Libère le flux créé par la méthode [`CreateResourceStream`](../createresourcestream).

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro d'une page. |
| resource | Ressource | La ressource HTML telle que police, style, image ou graphique. |
| resourceStream | Stream | Flux créé par la méthode [`CreateResourceStream`](../createresourcestream). |

### Voir aussi

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
