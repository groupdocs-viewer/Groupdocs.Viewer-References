---
title: Cache
second_title: GroupDocs.Viewer for Java API Reference
description: Defines methods required for storing rendered document and document resources u0441ache.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.caching/cache/
---```
public interface Cache
```

Defines methods required for storing rendered document and document resources \\u0441ache.
## Methods

| Method | Description |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserts a cache entry into the cache. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Gets the entry associated with this key if present and null otherwise. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all keys matching filter. |
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public abstract void set(String key, Object value)
```


Inserts a cache entry into the cache.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A unique identifier for the cache entry. |
| value | java.lang.Object | The object to insert. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public abstract T <T>get(String key, Class<T> clazz)
```


Gets the entry associated with this key if present and null otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |
| clazz | java.lang.Class<T> |  |

**Returns:**
T - Object if the key was found and null otherwise.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public abstract List<String> getKeys(String filter)
```


Returns all keys matching filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
java.util.List<java.lang.String> - Keys matching the filter.
