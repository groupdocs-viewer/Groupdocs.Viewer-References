---
title: "CacheKeys"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供检索缓存条目唯一标识符的方法。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

提供检索缓存条目唯一标识符的方法。

该类允许您根据不同参数（如文档路径、渲染选项和资源名称）生成缓存键。这些缓存键可用于存储和检索缓存数据，以实现高效的文档渲染。

示例用法：

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | 返回表示一组 [Attachment](../../com.groupdocs.viewer.results/attachment) 对象的缓存条目的唯一标识符。 |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | 检索表示附件文件的缓存条目的唯一标识符。 |
| [getViewInfoKey()](#getViewInfoKey--) | 检索表示 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 对象的缓存条目的唯一标识符。 |
| [getFileInfoKey()](#getFileInfoKey--) | 检索表示 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 对象的缓存条目的唯一标识符。 |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | 检索表示文件的缓存条目的唯一标识符。 |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | 检索表示页面文件的缓存条目的唯一标识符。 |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | 返回表示 [Resource](../../com.groupdocs.viewer.results/resource) 对象的缓存条目的唯一标识符。 |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | 返回用于搜索表示 [Resource](../../com.groupdocs.viewer.results/resource) 对象的缓存条目的过滤字符串。 |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


返回表示一组 [Attachment](../../com.groupdocs.viewer.results/attachment) 对象的缓存条目的唯一标识符。

**Returns:**
java.lang.String - 附件缓存条目的唯一标识符。
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


检索表示附件文件的缓存条目的唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attachmentId | java.lang.String | 附件的唯一标识符（在单个文件的上下文中）。 |

**Returns:**
java.lang.String - 附件文件缓存条目的唯一标识符。
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


检索表示 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 对象的缓存条目的唯一标识符。

**Returns:**
java.lang.String - 缓存条目的唯一标识符。
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


检索表示 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 对象的缓存条目的唯一标识符。

**Returns:**
java.lang.String - 表示 [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) 对象的缓存条目的唯一标识符。
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


检索表示文件的缓存条目的唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extension | java.lang.String | 文件名后缀（包括句点 \".\"），例如 \".doc\"。 |

**Returns:**
java.lang.String - 表示文件的缓存条目的唯一标识符。
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


检索表示页面文件的缓存条目的唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页面的编号。 |
| extension | java.lang.String | 文件名后缀（包括句点 \".\"），例如 \".doc\"。 |

**Returns:**
java.lang.String - 表示页面文件的缓存条目的唯一标识符。
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


返回表示 [Resource](../../com.groupdocs.viewer.results/resource) 对象的缓存条目的唯一标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页面的编号。 |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML 资源。 |

**Returns:**
java.lang.String - 缓存条目的唯一标识符。
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


返回用于搜索表示 [Resource](../../com.groupdocs.viewer.results/resource) 对象的缓存条目的过滤字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 页面的编号。 |

**Returns:**
java.lang.String - 用于搜索缓存条目的过滤字符串。
