---
title: "FileCache"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示本地磁盘缓存。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

表示本地磁盘缓存。


FileCache 类表示 GroupDocs.Viewer 组件中的本地磁盘缓存。
它提供在磁盘上存储和检索缓存数据的功能，以实现高效的文档渲染。


示例用法：

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


要使用 FileCache，您需要创建此类的实例并将其传递给 ViewerSettings 对象。
随后 Viewer 对象将在渲染文档时使用 FileCache 进行缓存。


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
您也可以通过实现 Cache 接口来自定义缓存。*

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | 创建一个新的实例 |
FileCache
类。
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | 创建一个新的实例 |
FileCache
类。
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | 创建一个新的实例 |
FileCache
类。
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | 创建一个新的实例 |
FileCache
类。
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | 获取缓存文件夹的相对或绝对路径。 |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | 要追加到缓存路径的子文件夹。 |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | 将数据序列化到本地磁盘。 |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | 如果存在，则反序列化与此键关联的数据。 |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | 返回所有文件名中包含过滤器的文件名。 |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


创建一个新的实例
FileCache
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cachePath | java.lang.String | 文档缓存将存储的相对或绝对路径。 |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


创建一个新的实例
FileCache
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | 文档缓存将存储的相对或绝对路径。 |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


创建一个新的实例
FileCache
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cachePath | java.lang.String | 文档缓存将存储的相对或绝对路径。 |
|
|  | cacheSubFolder | java.lang.String | 要追加到 cachePath 的子文件夹。 |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


创建一个新的实例
FileCache
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | 文档缓存将存储的相对或绝对路径。 |
|
|  | cacheSubFolder | java.lang.String | 要追加到 cachePath 的子文件夹。 |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


获取缓存文件夹的相对或绝对路径。


**Returns:**
java.lang.String - 缓存文件夹的路径。

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


要追加到缓存路径的子文件夹。


**Returns:**
java.lang.String - 要追加的子文件夹。

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


将数据序列化到本地磁盘。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 键 | java.lang.String | 缓存条目的唯一标识符。 |
|
|  | 值 | java.lang.Object | 要序列化的对象。 |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


如果存在，则反序列化与此键关联的数据。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 键 | java.lang.String | 标识请求条目的键。 |
|
|  | 类 | java.lang.Class<T> | 预期值的类。 |
|

**Returns:**
T - 找到的值或 null。

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


返回所有文件名中包含过滤器的文件名。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 过滤器 | java.lang.String | 要使用的过滤器。 |
|

**Returns:**
java.util.List<java.lang.String> - 文件名中包含过滤器的文件名列表。

