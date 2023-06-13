---
title: Cache
second_title: GroupDocs.Viewer for Java API Reference
description: Defines methods required for storing rendered documents and document resources cache.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.caching/cache/
---```
public interface Cache
```

Defines methods required for storing rendered documents and document resources cache.

The Cache interface defines the methods required for storing rendered documents and document resources cache in the GroupDocs.Viewer component. It provides a contract for implementing different cache mechanisms to enhance the performance of document rendering by caching frequently accessed data.

Example usage:

```

 // Implement a custom cache by implementing the Cache interface
 public class MyCustomCache implements Cache {
     // Implement the methods of the Cache interface based on your caching mechanism
     // ...
 }

 // Create an instance of your custom cache
 Cache myCache = new MyCustomCache();

 final ViewerSettings viewerSettings = new ViewerSettings();
 // Set the custom cache to viewerSettings
 viewerSettings.setCache(myCache);

 // Use the viewerSettings object for creating Viewer object to render document with custom cache
 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Note: The Cache interface allows you to implement custom cache mechanisms tailored to your specific requirements. GroupDocs.Viewer also provides built-in cache implementation such as [FileCache](../../com.groupdocs.viewer.caching/filecache).
## Methods

| Method | Description |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Inserts a cache entry into the cache. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Retrieves the entry associated with the specified key if it is present, and returns null otherwise. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Returns all keys that match the specified filter. |
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


Retrieves the entry associated with the specified key if it is present, and returns null otherwise.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | A key identifying the requested entry. |
| clazz | java.lang.Class<T> | The class type of the expected entry. |

**Returns:**
T - the entry associated with the key if found, or null otherwise.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public abstract List<String> getKeys(String filter)
```


Returns all keys that match the specified filter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filter | java.lang.String | The filter to use. |

**Returns:**
java.util.List<java.lang.String> - A list of keys that match the filter.
