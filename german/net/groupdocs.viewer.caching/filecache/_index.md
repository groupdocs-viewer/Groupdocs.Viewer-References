---
title: "FileCache"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt einen lokalen On‑Disk‑Cache dar."
type: docs
weight: 990
url: /de/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Stellt einen lokalen Festplatten-Cache dar.

```csharp
public class FileCache : ICache
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FileCache](filecache#constructor)(string) | Erstellt eine neue Instanz der Klasse [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | Erstellt eine neue Instanz der Klasse [`FileCache`](../filecache). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | Der relative oder absolute Pfad zum Cache‑Ordner. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | Der Unterordner, der an den [`CachePath`](./cachepath) angehängt wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | Gibt alle Dateinamen zurück, die den Filter im Dateinamen enthalten. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | Serialisiert Daten auf die lokale Festplatte. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | Deserialisiert Daten, die mit diesem Schlüssel verknüpft sind, falls vorhanden. |

### Siehe auch

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
