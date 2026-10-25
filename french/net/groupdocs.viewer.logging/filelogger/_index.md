---
title: "FileLogger"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Écrit les messages de journalisation dans le fichier."
type: docs
weight: 660
url: /fr/net/groupdocs.viewer.logging/filelogger/
---

## FileLogger class

Écrit les messages de journalisation dans le fichier.

```csharp
public class FileLogger : ILogger
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileLogger](filelogger)(string) | Créer un logger vers le fichier. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/filelogger/error)(string, Exception) | Écrit un message d'erreur dans la console. Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application. |
| [Trace](../../groupdocs.viewer.logging/filelogger/trace)(string) | Écrit un message de trace dans la console. Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application. |
| [Warning](../../groupdocs.viewer.logging/filelogger/warning)(string) | Écrit un message d'avertissement dans la console. Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application. |

### Voir aussi

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
