---
title: "Erreur"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Écrit un message d'erreur. Les messages du journal d'erreurs fournissent des informations sur les événements irrécupérables dans le flux de l'application."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Écrit un message d'erreur. Les messages du journal d'erreurs fournissent des informations sur les événements irrécupérables dans le flux de l'application.

```csharp
public void Error(string message, Exception exception)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| message | String | Le message d'erreur. |
| exception | Exception | L'exception. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *message* est nul. |
| ArgumentNullException | Lancé lorsque *exception* est nul. |

### Voir aussi

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
