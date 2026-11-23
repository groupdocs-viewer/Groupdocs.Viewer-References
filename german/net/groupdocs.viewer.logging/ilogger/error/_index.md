---
title: "Fehler"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Schreibt eine Fehlermeldung. Fehlermeldungen im Log liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

Schreibt eine Fehlermeldung. Fehlermeldungen im Log liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

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

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
