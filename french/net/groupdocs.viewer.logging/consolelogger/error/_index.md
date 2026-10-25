---
title: "Erreur"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Écrit un message d'erreur dans la console. Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer.logging/consolelogger/error/
---

## ConsoleLogger.Error method

Écrit un message d'erreur dans la console. Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.

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

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
