---
title: "GetPageKey"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Seitendatei darstellt."
type: docs
weight: 50
url: /de/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Seitendatei darstellt.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer der Seite. |
| Erweiterung | String | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

### Rückgabewert

Eindeutiger Bezeichner für den Cache-Eintrag, der die Seiten-Datei darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *pageNumber* kleiner oder gleich null ist. |
| ArgumentException | Wird ausgelöst, wenn *extension* null oder leer ist. |

### Siehe auch

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
