---
title: CacheKeys
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides methods to retrieve the unique identifier for a cache entry.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Provides methods to retrieve the unique identifier for a cache entry.

The class allows you to generate cache keys based on different parameters, such as the document path, rendering options, and resource name. These cache keys can be used to store and retrieve cached data for efficient document rendering.

Example usage:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## Fields

| Field | Description |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | Returns the unique identifier for the cache entry that represents a collection of [Attachment](../../com.groupdocs.viewer.results/attachment) objects. |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Retrieves the unique identifier for the cache entry representing an attachment file. |
| [getViewInfoKey()](#getViewInfoKey--) | Retrieves the unique identifier for the cache entry that represents a [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object. |
| [getFileInfoKey()](#getFileInfoKey--) | Retrieves the unique identifier for the cache entry that represents a [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object. |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | Retrieves the unique identifier for the cache entry that represents a file. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Retrieves the unique identifier for the cache entry that represents a page file. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Returns a unique identifier for the cache entry that represents a [Resource](../../com.groupdocs.viewer.results/resource) object. |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Returns a filter string to search for cache entries that represent [Resource](../../com.groupdocs.viewer.results/resource) objects. |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Returns the unique identifier for the cache entry that represents a collection of [Attachment](../../com.groupdocs.viewer.results/attachment) objects.

**Returns:**
java.lang.String - the unique identifier for the attachments cache entry.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Retrieves the unique identifier for the cache entry representing an attachment file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachmentId | java.lang.String | The unique identifier of the attachment (in the context of a single file). |

**Returns:**
java.lang.String - the unique identifier for the attachment file cache entry.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Retrieves the unique identifier for the cache entry that represents a [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.

**Returns:**
java.lang.String - the unique identifier for the cache entry.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Retrieves the unique identifier for the cache entry that represents a [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.

**Returns:**
java.lang.String - the unique identifier for the cache entry representing a [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Retrieves the unique identifier for the cache entry that represents a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:**
java.lang.String - the unique identifier for the cache entry representing a file.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Retrieves the unique identifier for the cache entry that represents a page file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| extension | java.lang.String | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:**
java.lang.String - the unique identifier for the cache entry representing a page file.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Returns a unique identifier for the cache entry that represents a [Resource](../../com.groupdocs.viewer.results/resource) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource. |

**Returns:**
java.lang.String - the unique identifier for the cache entry.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Returns a filter string to search for cache entries that represent [Resource](../../com.groupdocs.viewer.results/resource) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |

**Returns:**
java.lang.String - the filter string to search for cache entries.
