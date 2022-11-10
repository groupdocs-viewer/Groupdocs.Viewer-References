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
## Constructors

| Constructor | Description |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Creates new instance of [FileCache](../../com.groupdocs.viewer.caching/filecache) class. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Creates new instance of [FileCache](../../com.groupdocs.viewer.caching/filecache) class. |
## Methods

| Method | Description |
| --- | --- |
| [getCachePath()](#getCachePath--) | The Relative or absolute path to the cache folder. |
| [getCacheSubFolder()](#getCacheSubFolder--) | The sub-folder to append to the \#getCachePath().getCachePath(). |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Serializes data to the local disk. |
| [<T>get(String key)](#-T-get-java.lang.String-) | Deserializes data associated with this key if present. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all file names that contains filter in filename. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Creates new instance of [FileCache](../../com.groupdocs.viewer.caching/filecache) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.lang.String | Relative or absolute path where document cache will be stored. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Creates new instance of [FileCache](../../com.groupdocs.viewer.caching/filecache) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cachePath | java.lang.String | Relative or absolute path where document cache will be stored. |
| cacheSubFolder | java.lang.String | The sub-folder to append to  cachePath . |

### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


The Relative or absolute path to the cache folder.

**Returns:**
java.lang.String - The Relative or absolute path to the cache folder.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


The sub-folder to append to the \#getCachePath().getCachePath().

**Returns:**
java.lang.String - The sub-folder to append to the \#getCachePath().getCachePath().
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Serializes data to the local disk.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | An unique identifier for the cache entry. |
| value | java.lang.Object | The object to serialize. |

### <T>get(String key) {#-T-get-java.lang.String-}
```
public final T <T>get(String key)
```


Deserializes data associated with this key if present.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |

**Returns:**
T - The located value or null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Returns all file names that contains filter in filename.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
java.util.List<java.lang.String> - File names that contains filter in filename.
