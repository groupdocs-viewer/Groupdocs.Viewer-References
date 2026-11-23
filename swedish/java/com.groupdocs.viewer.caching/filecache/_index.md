---
title: "FileCache"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar en lokal cache på disk."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Representerar en lokal cache på disk.


FileCache-klassen representerar en lokal cache på disk i GroupDocs.Viewer-komponenten.
Den tillhandahåller funktionalitet för att lagra och hämta cachad data på disken för effektiv dokumentrendering.


Exempel på användning:

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


För att använda FileCache måste du skapa en instans av denna klass och skicka den till ViewerSettings-objektet.
Viewer-objektet kommer sedan att använda FileCache för cachningsändamål när dokument renderas.


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
Du kan också implementera din egen anpassade cache genom att implementera Cache-gränssnittet.*

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Skapar en ny instans av |
FileCache
klassen.
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Skapar en ny instans av |
FileCache
klassen.
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Skapar en ny instans av |
FileCache
klassen.
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Skapar en ny instans av |
FileCache
klassen.
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | Hämtar den relativa eller absoluta sökvägen till cache-mappen. |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | Undermappen som ska läggas till cache-sökvägen. |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serialiserar data till den lokala disken. |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserialiserar data som är associerad med denna nyckel om den finns. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Returnerar alla filnamn som innehåller filtret i filnamnet. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Skapar en ny instans av
FileCache
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cachePath | java.lang.String | Den relativa eller absoluta sökvägen där dokumentcachen kommer att lagras. |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Skapar en ny instans av
FileCache
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Den relativa eller absoluta sökvägen där dokumentcachen kommer att lagras. |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Skapar en ny instans av
FileCache
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cachePath | java.lang.String | Den relativa eller absoluta sökvägen där dokumentcachen kommer att lagras. |
|
|  | cacheSubFolder | java.lang.String | Undermappen att lägga till i cachePath. |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Skapar en ny instans av
FileCache
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | Den relativa eller absoluta sökvägen där dokumentcachen kommer att lagras. |
|
|  | cacheSubFolder | java.lang.String | Undermappen att lägga till i cachePath. |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Hämtar den relativa eller absoluta sökvägen till cache-mappen.


**Returns:**
java.lang.String - Sökväg till cache-mappen.

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Undermappen som ska läggas till cache-sökvägen.


**Returns:**
java.lang.String - undermappen att lägga till.

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serialiserar data till den lokala disken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nyckel | java.lang.String | Den unika identifieraren för cache-posten. |
|
|  | värde | java.lang.Object | Objektet som ska serialiseras. |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserialiserar data som är associerad med denna nyckel om den finns.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nyckel | java.lang.String | En nyckel som identifierar den begärda posten. |
|
|  | klass | java.lang.Class<T> | Klassen för det förväntade värdet. |
|

**Returns:**
T - det hittade värdet eller null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Returnerar alla filnamn som innehåller filtret i filnamnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filter | java.lang.String | Filtret att använda. |
|

**Returns:**
java.util.List<java.lang.String> - Filnamn som innehåller filtret i filnamnet.

