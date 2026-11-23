---
title: "FileCache"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente un cache local sur disque."
type: docs
weight: 990
url: /fr/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Représente un cache local sur disque.

```csharp
public class FileCache : ICache
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Crée une nouvelle instance de la classe [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | Crée une nouvelle instance de la classe [`FileCache`](../filecache). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | Le chemin relatif ou absolu du dossier de cache. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | Le sous-dossier à ajouter au [`CachePath`](./cachepath). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Renvoie tous les noms de fichiers qui contiennent le filtre dans le nom de fichier. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Sérialise les données sur le disque local. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Désérialise les données associées à cette clé si elles sont présentes. |

### Voir aussi

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
