---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "定义用于自定义 Viewer 组件行为的设置。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

定义用于自定义 Viewer 组件行为的设置。

ViewerSettings 类提供选项和属性，以自定义 GroupDocs.Viewer 组件在文档渲染过程中的行为。您可以使用此类指定各种设置，例如记录器、自定义缓存实现等。

示例用法：

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | 初始化 ViewerSettings 类的新实例。 |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | 初始化 ViewerSettings 类的新实例。 |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | 初始化 ViewerSettings 类的新实例。 |
| [ViewerSettings()](#ViewerSettings--) | 初始化 ViewerSettings 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLogger()](#getLogger--) | 获取用于日志记录（错误、警告、跟踪）的记录器实现。 |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 设置用于日志记录（错误、警告、跟踪）的记录器实现。 |
| [getCache()](#getCache--) | 获取用于存储渲染结果的缓存实现。 |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | 设置用于存储渲染结果的缓存实现。 |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


初始化 ViewerSettings 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 缓存。 |
| 记录器 | com.groupdocs.foundation.logging.ILogger | 记录器。 |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


初始化 ViewerSettings 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 记录器 | com.groupdocs.foundation.logging.ILogger | 记录器。 |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


初始化 ViewerSettings 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 缓存。 |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


初始化 ViewerSettings 类的新实例。

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


获取用于日志记录（错误、警告、跟踪）的记录器实现。

**Returns:**
com.groupdocs.foundation.logging.ILogger - 记录器实现。
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


设置用于日志记录（错误、警告、跟踪）的记录器实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 记录器 | com.groupdocs.foundation.logging.ILogger | 要设置的记录器实现。 |

### getCache() {#getCache--}
```
public final Cache getCache()
```


获取用于存储渲染结果的缓存实现。

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.
### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


设置用于存储渲染结果的缓存实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | 缓存实现。 |

