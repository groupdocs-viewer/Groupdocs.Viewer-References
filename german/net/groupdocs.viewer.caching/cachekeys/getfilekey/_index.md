---
title: "GetFileKey"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Datei darstellt."
type: docs
weight: 40
url: /de/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Datei darstellt.

```csharp
public static string GetFileKey(string extension)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Erweiterung | String | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

### Rückgabewert

Eindeutiger Bezeichner für den Cache-Eintrag, der die Datei darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *extension* null oder leer ist. |

### Siehe auch

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
