---
title: "Fehler"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Schreibt eine Fehlermeldung in die Konsole. Fehlermeldungen im Log liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf."
type: docs
weight: 20
url: /de/net/groupdocs.viewer.logging/consolelogger/error/
---

## ConsoleLogger.Error method

Schreibt eine Fehlermeldung in die Konsole. Fehlermeldungen im Log liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

```csharp
public void Error(string message, Exception exception)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Nachricht | String | Die Fehlermeldung. |
| Ausnahme | Ausnahme | Die Ausnahme. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *message* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *exception* null ist. |

### Siehe auch

* class [ConsoleLogger](../../consolelogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
