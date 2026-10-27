---
title: "FileCache"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een lokale cache op schijf voor."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Stelt een lokale cache op schijf voor.

De FileCache‑klasse vertegenwoordigt een lokale cache op schijf in de GroupDocs.Viewer‑component. Het biedt functionaliteit om gecachte gegevens op de schijf op te slaan en op te halen voor efficiënte documentweergave.

Voorbeeldgebruik:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Om de FileCache te gebruiken, moet u een instantie van deze klasse maken en deze doorgeven aan het ViewerSettings‑object. Het Viewer‑object zal vervolgens de FileCache gebruiken voor cachingdoeleinden tijdens het renderen van documenten.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Maakt een nieuwe instantie van de  FileCache  klasse. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Maakt een nieuwe instantie van de  FileCache  klasse. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Maakt een nieuwe instantie van de  FileCache  klasse. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Maakt een nieuwe instantie van de  FileCache  klasse. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCachePath()](#getCachePath--) | Haalt het relatieve of absolute pad op naar de cache‑map. |
| [getCacheSubFolder()](#getCacheSubFolder--) | De submap die aan het cache‑pad moet worden toegevoegd. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serialiseert gegevens naar de lokale schijf. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserialiseert gegevens die aan deze sleutel zijn gekoppeld, indien aanwezig. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Retourneert alle bestandsnamen die de filter in de bestandsnaam bevatten. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Maakt een nieuwe instantie van de  FileCache  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cachePath | java.lang.String | Het relatieve of absolute pad waar de documentcache wordt opgeslagen. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Maakt een nieuwe instantie van de  FileCache  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Het relatieve of absolute pad waar de documentcache wordt opgeslagen. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Maakt een nieuwe instantie van de  FileCache  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cachePath | java.lang.String | Het relatieve of absolute pad waar de documentcache wordt opgeslagen. |
| cacheSubFolder | java.lang.String | De submap die moet worden toegevoegd aan cachePath. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Maakt een nieuwe instantie van de  FileCache  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Het relatieve of absolute pad waar de documentcache wordt opgeslagen. |
| cacheSubFolder | java.lang.String | De submap die moet worden toegevoegd aan cachePath. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Haalt het relatieve of absolute pad op naar de cache‑map.

**Returns:**
java.lang.String - Pad naar de cachemap.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


De submap die aan het cache‑pad moet worden toegevoegd.

**Returns:**
java.lang.String - de submap die moet worden toegevoegd.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serialiseert gegevens naar de lokale schijf.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | De unieke identificatie voor de cache‑vermelding. |
| value | java.lang.Object | Het object om te serialiseren. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserialiseert gegevens die aan deze sleutel zijn gekoppeld, indien aanwezig.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | java.lang.String | Een sleutel die de gevraagde vermelding identificeert. |
| clazz | java.lang.Class<T> | De klasse van de verwachte waarde. |

**Returns:**
T - de gevonden waarde of null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Retourneert alle bestandsnamen die de filter in de bestandsnaam bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filter | java.lang.String | De te gebruiken filter. |

**Returns:**
java.util.List<java.lang.String> - Bestandsnamen die de filter in de bestandsnaam bevatten.
