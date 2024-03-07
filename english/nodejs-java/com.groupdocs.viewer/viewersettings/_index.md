---
title: ViewerSettings
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Defines settings for customizing the behavior of the Viewer component.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Defines settings for customizing the behavior of the Viewer component.

The ViewerSettings class provides options and properties to customize the behavior of the GroupDocs.Viewer component during the document rendering process. You can use this class to specify various settings, such as logger, custom cache implementation, and more.

Example usage:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initializes a new instance of the  ViewerSettings  class. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initializes a new instance of the  ViewerSettings  class. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initializes a new instance of the  ViewerSettings  class. |
| [ViewerSettings()](#ViewerSettings--) | Initializes a new instance of the  ViewerSettings  class. |
## Methods

| Method | Description |
| --- | --- |
| [getLogger()](#getLogger--) | Gets the logger implementation used for logging (Errors, Warnings, Traces). |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Sets the logger implementation used for logging (Errors, Warnings, Traces). |
| [getCache()](#getCache--) | Gets the cache implementation used for storing rendering results. |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Sets the cache implementation used for storing rendering results. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initializes a new instance of the  ViewerSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | The cache. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initializes a new instance of the  ViewerSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initializes a new instance of the  ViewerSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | The cache. |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Initializes a new instance of the  ViewerSettings  class.

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Gets the logger implementation used for logging (Errors, Warnings, Traces).

**Returns:**
com.groupdocs.foundation.logging.ILogger - the logger implementation.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Sets the logger implementation used for logging (Errors, Warnings, Traces).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The logger implementation to set. |

### getCache() {#getCache--}
```
public final Cache getCache()
```


Gets the cache implementation used for storing rendering results.

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.
### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Sets the cache implementation used for storing rendering results.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | The cache implementation. |

