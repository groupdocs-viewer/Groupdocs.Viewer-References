---
title: "GetAttachmentKey"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Anhangsdatei darstellt."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Anhangsdatei darstellt.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| attachmentId | String | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |

### Rückgabewert

Eindeutiger Bezeichner für den Cache-Eintrag, der die Anhangsdatei darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *attachmentId* null oder leer ist. |

### Siehe auch

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
