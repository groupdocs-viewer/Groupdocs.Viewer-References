---
title: "CacheKeys"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Fournit des méthodes pour récupérer l'identifiant unique de l'entrée du cache."
type: docs
weight: 980
url: /fr/net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

Fournit des méthodes pour récupérer l'identifiant unique de l'entrée du cache.

```csharp
public static class CacheKeys
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de pièce jointe. |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | Renvoie l'identifiant unique de l'entrée du cache qui représente la collection d'objets [`Attachment`](../../groupdocs.viewer.results/attachment). |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | Renvoie l'identifiant unique de l'entrée du cache qui représente l'objet [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier. |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de page. |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | Renvoie la chaîne de filtre pour rechercher les entrées du cache qui représentent des objets [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | Renvoie l'identifiant unique de l'entrée du cache qui représente l'objet [`Resource`](../../groupdocs.viewer.results/resource). |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | Renvoie l'identifiant unique de l'entrée du cache qui représente l'objet [`ViewInfo`](../../groupdocs.viewer.results/viewinfo). |

### Voir aussi

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
