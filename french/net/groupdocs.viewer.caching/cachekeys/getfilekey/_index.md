---
title: "GetFileKey"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier.

```csharp
public static string GetFileKey(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | Le suffixe du nom de fichier (y compris le point ".") par ex. ".doc". |

### Valeur de retour

Identifiant unique pour l'entrée du cache qui représente le fichier.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *extension* est nul ou vide. |

### Voir aussi

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
