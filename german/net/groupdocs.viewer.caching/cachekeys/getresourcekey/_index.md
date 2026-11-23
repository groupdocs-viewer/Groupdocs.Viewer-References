---
title: "GetResourceKey"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt den eindeutigen Bezeichner für den Cache-Eintrag zurück, der das Objekt Resourcegroupdocs.viewer.results/resource darstellt."
type: docs
weight: 70
url: /de/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

Gibt den eindeutigen Bezeichner für den Cache-Eintrag zurück, der das Objekt [`Resource`](../../../groupdocs.viewer.results/resource) darstellt.

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer der Seite. |
| Ressource | Resource | Die HTML-Ressource. |

### Rückgabewert

Eindeutiger Bezeichner für den Cache-Eintrag, der das Objekt [`Resource`](../../../groupdocs.viewer.results/resource) darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *pageNumber* kleiner oder gleich null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *resource* null ist. |

### Siehe auch

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
