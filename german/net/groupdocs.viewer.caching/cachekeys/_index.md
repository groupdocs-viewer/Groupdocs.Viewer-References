---
title: "CacheKeys"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt Methoden zum Abrufen einer eindeutigen Kennung für den Cache-Eintrag bereit."
type: docs
weight: 980
url: /de/net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

Stellt Methoden zum Abrufen einer eindeutigen Kennung für den Cache-Eintrag bereit.

```csharp
public static class CacheKeys
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Anhangsdatei darstellt. |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Sammlung von [`Attachment`](../../groupdocs.viewer.results/attachment)-Objekten darstellt. |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der das [`ViewInfo`](../../groupdocs.viewer.results/viewinfo)-Objekt darstellt. |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Datei darstellt. |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der die Seitendatei darstellt. |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | Gibt den Filterstring zurück, um nach Cache‑Einträgen zu suchen, die [`Resource`](../../groupdocs.viewer.results/resource)-Objekte darstellen. |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der das [`Resource`](../../groupdocs.viewer.results/resource)-Objekt darstellt. |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | Gibt die eindeutige Kennung für den Cache‑Eintrag zurück, der das [`ViewInfo`](../../groupdocs.viewer.results/viewinfo)-Objekt darstellt. |

### Siehe auch

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
