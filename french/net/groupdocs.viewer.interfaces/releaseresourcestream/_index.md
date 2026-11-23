---
title: "ReleaseResourceStream"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Libère le flux qui a été instancié par la méthode associée au délégué CreateResourceStream./createresourcestream."
type: docs
weight: 730
url: /fr/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

Libère le flux qui a été instancié par la méthode associée au délégué [`CreateResourceStream`](../createresourcestream).

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de la page. |
| resource | Ressource | Ressource HTML telle que police, style, image ou graphique. |
| resourceStream | Stream | Le flux créé par la méthode associée au délégué [`CreateResourceStream`](../createresourcestream). |

### Voir aussi

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
