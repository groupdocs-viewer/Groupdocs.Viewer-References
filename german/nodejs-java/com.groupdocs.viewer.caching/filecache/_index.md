---
title: "FileCache"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt einen lokalen Festplattencache dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Stellt einen lokalen Festplattencache dar.

Die FileCache‑Klasse repräsentiert einen lokalen Festplatten‑Cache in der GroupDocs.Viewer‑Komponente. Sie bietet Funktionalität zum Speichern und Abrufen von zwischengespeicherten Daten auf der Festplatte für eine effiziente Dokumentendarstellung.

Beispielhafte Verwendung:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Um die FileCache zu verwenden, müssen Sie eine Instanz dieser Klasse erstellen und sie dem ViewerSettings‑Objekt übergeben. Das Viewer‑Objekt verwendet dann die FileCache für Caching‑Zwecke beim Rendern von Dokumenten.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Erstellt eine neue Instanz der  FileCache  Klasse. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Erstellt eine neue Instanz der  FileCache  Klasse. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Erstellt eine neue Instanz der  FileCache  Klasse. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Erstellt eine neue Instanz der  FileCache  Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCachePath()](#getCachePath--) | Gibt den relativen oder absoluten Pfad zum Cache‑Ordner zurück. |
| [getCacheSubFolder()](#getCacheSubFolder--) | Der Unterordner, der dem Cache‑Pfad angehängt wird. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serialisiert Daten auf die lokale Festplatte. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserialisiert Daten, die mit diesem Schlüssel verknüpft sind, falls vorhanden. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Gibt alle Dateinamen zurück, die den Filter im Dateinamen enthalten. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Erstellt eine neue Instanz der  FileCache  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | java.lang.String | Der relative oder absolute Pfad, an dem der Dokumenten-Cache gespeichert wird. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Erstellt eine neue Instanz der  FileCache  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Der relative oder absolute Pfad, an dem der Dokumenten-Cache gespeichert wird. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Erstellt eine neue Instanz der  FileCache  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | java.lang.String | Der relative oder absolute Pfad, an dem der Dokumenten-Cache gespeichert wird. |
| cacheSubFolder | java.lang.String | Der Unterordner, der an cachePath angehängt werden soll. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Erstellt eine neue Instanz der  FileCache  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Der relative oder absolute Pfad, an dem der Dokumenten-Cache gespeichert wird. |
| cacheSubFolder | java.lang.String | Der Unterordner, der an cachePath angehängt werden soll. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Gibt den relativen oder absoluten Pfad zum Cache‑Ordner zurück.

**Returns:**
java.lang.String - Pfad zum Cache-Ordner.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Der Unterordner, der dem Cache‑Pfad angehängt wird.

**Returns:**
java.lang.String - der anzuhängende Unterordner.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serialisiert Daten auf die lokale Festplatte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Der eindeutige Bezeichner für den Cache-Eintrag. |
| value | java.lang.Object | Das zu serialisierende Objekt. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserialisiert Daten, die mit diesem Schlüssel verknüpft sind, falls vorhanden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | java.lang.String | Ein Schlüssel, der den angeforderten Eintrag identifiziert. |
| clazz | java.lang.Class<T> | Die Klasse des erwarteten Werts. |

**Returns:**
T - der gefundene Wert oder null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Gibt alle Dateinamen zurück, die den Filter im Dateinamen enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filter | java.lang.String | Der zu verwendende Filter. |

**Returns:**
java.util.List<java.lang.String> - Dateinamen, die den Filter im Dateinamen enthalten.
