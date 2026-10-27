---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Viewer bileşeninin davranışını özelleştirmek için ayarları tanımlar."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Viewer bileşeninin davranışını özelleştirmek için ayarları tanımlar.

ViewerSettings sınıfı, belge renderleme süreci sırasında GroupDocs.Viewer bileşeninin davranışını özelleştirmek için seçenekler ve özellikler sağlar. Bu sınıfı, logger, özel önbellek uygulaması gibi çeşitli ayarları belirtmek için kullanabilirsiniz.

Örnek kullanım:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | ViewerSettings sınıfının yeni bir örneğini başlatır. |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | ViewerSettings sınıfının yeni bir örneğini başlatır. |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | ViewerSettings sınıfının yeni bir örneğini başlatır. |
| [ViewerSettings()](#ViewerSettings--) | ViewerSettings sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLogger()](#getLogger--) | Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulamasını alır. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulamasını ayarlar. |
| [getCache()](#getCache--) | Renderleme sonuçlarını depolamak için kullanılan önbellek uygulamasını alır. |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Renderleme sonuçlarını depolamak için kullanılan önbellek uygulamasını ayarlar. |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


ViewerSettings sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek. |
| logger | com.groupdocs.foundation.logging.ILogger | Logger. |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


ViewerSettings sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Logger. |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


ViewerSettings sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek. |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


ViewerSettings sınıfının yeni bir örneğini başlatır.

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulamasını alır.

**Returns:**
com.groupdocs.foundation.logging.ILogger - logger uygulaması.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Ayarlanacak logger uygulaması. |

### getCache() {#getCache--}
```
public final Cache getCache()
```


Renderleme sonuçlarını depolamak için kullanılan önbellek uygulamasını alır.

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.
### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Renderleme sonuçlarını depolamak için kullanılan önbellek uygulamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek uygulaması. |

