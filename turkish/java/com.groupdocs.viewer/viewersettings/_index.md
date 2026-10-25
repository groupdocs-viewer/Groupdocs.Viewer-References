---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Viewer bileşeninin davranışını özelleştirmek için ayarları tanımlar."
type: docs
weight: 13
url: /tr/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Viewer bileşeninin davranışını özelleştirmek için ayarları tanımlar.


ViewerSettings sınıfı, belge işleme sürecinde GroupDocs.Viewer bileşeninin davranışını özelleştirmek için seçenekler ve özellikler sağlar.
Bu sınıfı, günlük kaydedici, özel önbellek uygulaması ve daha fazlası gibi çeşitli ayarları belirtmek için kullanabilirsiniz.


Örnek kullanım:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Yeni bir örnek başlatır |
ViewerSettings
sınıf.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Yeni bir örnek başlatır |
ViewerSettings
sınıf.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Yeni bir örnek başlatır |
ViewerSettings
sınıf.
|
|  | [ViewerSettings()](#ViewerSettings--) | Yeni bir örnek başlatır |
ViewerSettings
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getLogger()](#getLogger--) | Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan günlük kaydedici uygulamasını alır. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan günlük kaydedici uygulamasını ayarlar. |
|
|  | [getCache()](#getCache--) | İşleme sonuçlarını depolamak için kullanılan önbellek uygulamasını alır. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | İşleme sonuçlarını depolamak için kullanılan önbellek uygulamasını ayarlar. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Yeni bir örnek başlatır
ViewerSettings
sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek. |
|
|  | günlükleyici | com.groupdocs.foundation.logging.ILogger | Günlük kaydedici. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Yeni bir örnek başlatır
ViewerSettings
sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | günlükleyici | com.groupdocs.foundation.logging.ILogger | Günlük kaydedici. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Yeni bir örnek başlatır
ViewerSettings
sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Yeni bir örnek başlatır
ViewerSettings
sınıf.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan günlük kaydedici uygulamasını alır.


**Returns:**
com.groupdocs.foundation.logging.ILogger - günlük kaydedici uygulaması.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Günlük kaydı (Hatalar, Uyarılar, İzlemeler) için kullanılan günlük kaydedici uygulamasını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | günlükleyici | com.groupdocs.foundation.logging.ILogger | Ayarlanacak günlük kaydedici uygulaması. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


İşleme sonuçlarını depolamak için kullanılan önbellek uygulamasını alır.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


İşleme sonuçlarını depolamak için kullanılan önbellek uygulamasını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Önbellek uygulaması. |
|

