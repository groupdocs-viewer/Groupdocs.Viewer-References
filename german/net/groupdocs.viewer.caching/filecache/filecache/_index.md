---
title: FileCache
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Erstellt eine neue Instanz vonFileCachegroupdocs.viewer.caching/filecache Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.viewer.caching/filecache/filecache/
---
## FileCache(string) {#constructor}

Erstellt eine neue Instanz von[`FileCache`](../../filecache) Klasse.

```csharp
public FileCache(string cachePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | String | Relativer oder absoluter Pfad, in dem der Dokumentcache gespeichert wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*cachePath* ist Null. |

### Siehe auch

* class [FileCache](../../filecache)
* namensraum [GroupDocs.Viewer.Caching](../../filecache)
* Montage [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

Erstellt eine neue Instanz von[`FileCache`](../../filecache) Klasse.

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | String | Relativer oder absoluter Pfad, in dem der Dokumentcache gespeichert wird. |
| cacheSubFolder | String | Der Unterordner, an den angehängt werden soll*cachePath*. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*cachePath* ist Null. |
| ArgumentNullException | Wann geworfen*cacheSubFolder* ist Null. |

### Siehe auch

* class [FileCache](../../filecache)
* namensraum [GroupDocs.Viewer.Caching](../../filecache)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->