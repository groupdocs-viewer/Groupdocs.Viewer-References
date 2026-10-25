---
title: "GetAttachmentKey"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de pièce jointe."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

Renvoie l'identifiant unique de l'entrée du cache qui représente le fichier de pièce jointe.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| attachmentId | String | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |

### Valeur de retour

Identifiant unique de l'entrée du cache qui représente le fichier de la pièce jointe.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *attachmentId* est nul ou vide. |

### Voir aussi

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
