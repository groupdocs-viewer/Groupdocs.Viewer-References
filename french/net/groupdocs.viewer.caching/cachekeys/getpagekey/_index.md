---
title: "GetPageKey"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de page."
type: docs
weight: 50
url: /fr/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de page.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de la page. |
| extension | String | Le suffixe du nom de fichier (y compris le point ".") par ex. ".doc". |

### Valeur de retour

Identifiant unique de l'entrée du cache qui représente le fichier de page.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *pageNumber* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *extension* est nul ou vide. |

### Voir aussi

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
