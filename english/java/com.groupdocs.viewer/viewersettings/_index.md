---
title: ViewerSettings
second_title: GroupDocs.Viewer for Java API Reference
description: Defines settings for customizing  behaviour.
type: docs
weight: 13
url: /java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Defines settings for customizing [Viewer](../../com.groupdocs.viewer/viewer) behaviour.
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class. |
## Methods

| Method | Description |
| --- | --- |
| [getLogger()](#getLogger--) | The logger implementation used for logging (Errors, Warnings, Traces). |
| [getCache()](#getCache--) | The cache implementation used for storing rendering results. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | The cache. |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The logger. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Initializes new instance of [ViewerSettings](../../com.groupdocs.viewer/viewersettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | The cache. |

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


The logger implementation used for logging (Errors, Warnings, Traces).

**Returns:**
com.groupdocs.foundation.logging.ILogger
### getCache() {#getCache--}
```
public final Cache getCache()
```


The cache implementation used for storing rendering results.

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache)
