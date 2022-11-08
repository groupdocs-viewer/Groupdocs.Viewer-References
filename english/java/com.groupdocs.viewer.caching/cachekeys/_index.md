---
title: CacheKeys
second_title: GroupDocs.Viewer for Java API Reference
description: Provides methods to retrieve unique identifier for the cache entry.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Provides methods to retrieve unique identifier for the cache entry.
## Constructors

| Constructor | Description |
| --- | --- |
| [CacheKeys()](#CacheKeys--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | Returns unique identifier for the cache entry that represents collection of [Attachment](../../com.groupdocs.viewer.results/attachment) objects. |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Returns unique identifier for the cache entry that represents attachment file. |
| [getViewInfoKey()](#getViewInfoKey--) | Returns unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object. |
| [getFileInfoKey()](#getFileInfoKey--) | Returns unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object. |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | Returns unique identifier for the cache entry that represents file. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Returns unique identifier for the cache entry that represents page file. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Returns unique identifier for the cache entry that represents [Resource](../../com.groupdocs.viewer.results/resource) object. |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Returns filter string to search for cache entries that represents [Resource](../../com.groupdocs.viewer.results/resource) objects. |
### CacheKeys() {#CacheKeys--}
```
public CacheKeys()
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Returns unique identifier for the cache entry that represents collection of [Attachment](../../com.groupdocs.viewer.results/attachment) objects.

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents collection of [Attachment](../../com.groupdocs.viewer.results/attachment) objects.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Returns unique identifier for the cache entry that represents attachment file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attachmentId | java.lang.String | Unique (in context of single file) identifier of the attachment. |

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents attachment file.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Returns unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Returns unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) object.
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Returns unique identifier for the cache entry that represents file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents file.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Returns unique identifier for the cache entry that represents page file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| extension | java.lang.String | The filename suffix (including the period ".") e.g. ".doc". |

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents page file.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Returns unique identifier for the cache entry that represents [Resource](../../com.groupdocs.viewer.results/resource) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of the page. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | The HTML resource. |

**Returns:**
java.lang.String - Unique identifier for the cache entry that represents [Resource](../../com.groupdocs.viewer.results/resource) object.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Returns filter string to search for cache entries that represents [Resource](../../com.groupdocs.viewer.results/resource) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | The number of page. |

**Returns:**
java.lang.String - Filter string to search for cache entries that represents [Resource](../../com.groupdocs.viewer.results/resource) objects.
