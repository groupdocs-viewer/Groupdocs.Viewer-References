---
title: "FileCache"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Crée une nouvelle instance de la classe FileCachegroupdocs.viewer.caching/filecache."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

Crée une nouvelle instance de la classe [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cachePath | String | Chemin relatif ou absolu où le cache du document sera stocké. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *cachePath* est nul. |

### Voir aussi

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

Crée une nouvelle instance de la classe [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| cachePath | String | Chemin relatif ou absolu où le cache du document sera stocké. |
| cacheSubFolder | String | Le sous-dossier à ajouter à *cachePath*. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *cachePath* est nul. |
| ArgumentNullException | Lancé lorsque *cacheSubFolder* est nul. |

### Voir aussi

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
