---
title: FileCache
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a local on-disk cache.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Represents a local on-disk cache.

The FileCache class represents a local on-disk cache in the GroupDocs.Viewer component. It provides functionality to store and retrieve cached data on the disk for efficient document rendering.

Example usage:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

To use the FileCache, you need to create an instance of this class and pass it to the ViewerSettings object. The Viewer object will then use the FileCache for caching purposes while rendering documents.

Note: The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Creates a new instance of the  FileCache  class. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Creates a new instance of the  FileCache  class. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Creates a new instance of the  FileCache  class. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Creates a new instance of the  FileCache  class. |
## Fields

| Field | Description |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCachePath()](#getCachePath--) | Gets the relative or absolute path to the cache folder. |
| [getCacheSubFolder()](#getCacheSubFolder--) | The sub-folder to append to the cache path. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serializes data to the local disk. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Deserializes data associated with this key if present. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all file names that contain the filter in the filename. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Creates a new instance of the  FileCache  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.lang.String | The relative or absolute path where the document cache will be stored. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Creates a new instance of the  FileCache  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.nio.file.Path | The relative or absolute path where the document cache will be stored. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Creates a new instance of the  FileCache  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.lang.String | The relative or absolute path where the document cache will be stored. |
| cacheSubFolder | java.lang.String | The sub-folder to append to  cachePath . |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Creates a new instance of the  FileCache  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.nio.file.Path | The relative or absolute path where the document cache will be stored. |
| cacheSubFolder | java.lang.String | The sub-folder to append to  cachePath . |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Gets the relative or absolute path to the cache folder.

**Returns:**
java.lang.String - Path to the cache folder.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


The sub-folder to append to the cache path.

**Returns:**
java.lang.String - the sub-folder to append.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serializes data to the local disk.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The unique identifier for the cache entry. |
| value | java.lang.Object | The object to serialize. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Deserializes data associated with this key if present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |
| clazz | java.lang.Class<T> | The class of the expected value. |

**Returns:**
T - the located value or null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Returns all file names that contain the filter in the filename.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
java.util.List<java.lang.String> - File names that contain the filter in the filename.
