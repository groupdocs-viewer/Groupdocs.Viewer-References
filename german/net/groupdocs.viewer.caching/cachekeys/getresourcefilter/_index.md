---
title: "GetResourceFilter"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt die Filterzeichenfolge zurück, um nach Cache-Einträgen zu suchen, die Resourcegroupdocs.viewer.results/resource-Objekte darstellen."
type: docs
weight: 60
url: /de/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

Gibt die Filterzeichenfolge zurück, um nach Cache-Einträgen zu suchen, die [`Resource`](../../../groupdocs.viewer.results/resource)-Objekte darstellen.

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Nummer der Seite. |

### Rückgabewert

Filterzeichenfolge, um nach Cache-Einträgen zu suchen, die [`Resource`](../../../groupdocs.viewer.results/resource)-Objekte darstellen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *pageNumber* kleiner oder gleich null ist. |

### Siehe auch

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
