---
title: "FileCache"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Yerel disk üzerindeki bir önbelleği temsil eder."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Yerel disk üzerindeki bir önbelleği temsil eder.

FileCache sınıfı, GroupDocs.Viewer bileşeninde yerel bir disk üzerindeki önbelleği temsil eder. Belgelerin verimli bir şekilde işlenmesi için önbelleğe alınmış verileri diske kaydetme ve geri alma işlevselliği sağlar.

Örnek kullanım:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

FileCache'i kullanmak için bu sınıfın bir örneğini oluşturmalı ve ViewerSettings nesnesine geçirmelisiniz. Viewer nesnesi, belgeleri işlerken önbellekleme amacıyla FileCache'i kullanacaktır.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | FileCache sınıfının yeni bir örneğini oluşturur. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | FileCache sınıfının yeni bir örneğini oluşturur. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | FileCache sınıfının yeni bir örneğini oluşturur. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | FileCache sınıfının yeni bir örneğini oluşturur. |
## Fields

| Field | Açıklama |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCachePath()](#getCachePath--) | Önbellek klasörünün göreli ya da mutlak yolunu alır. |
| [getCacheSubFolder()](#getCacheSubFolder--) | Önbellek yoluna eklenecek alt klasör. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Verileri yerel diske serileştirir. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Bu anahtarla ilişkili veri mevcutsa seriden çıkarır. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Dosya adında filtreyi içeren tüm dosya adlarını döndürür. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


FileCache sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cachePath | java.lang.String | Belge önbelleğinin saklanacağı göreli ya da mutlak yol. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


FileCache sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Belge önbelleğinin saklanacağı göreli ya da mutlak yol. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


FileCache sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cachePath | java.lang.String | Belge önbelleğinin saklanacağı göreli ya da mutlak yol. |
| cacheSubFolder | java.lang.String | cachePath'e eklenecek alt klasör. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


FileCache sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Belge önbelleğinin saklanacağı göreli ya da mutlak yol. |
| cacheSubFolder | java.lang.String | cachePath'e eklenecek alt klasör. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Önbellek klasörünün göreli ya da mutlak yolunu alır.

**Returns:**
java.lang.String - Önbellek klasörünün yolu.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Önbellek yoluna eklenecek alt klasör.

**Returns:**
java.lang.String - eklenecek alt klasör.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Verileri yerel diske serileştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | Önbellek girdisi için benzersiz tanımlayıcı. |
| value | java.lang.Object | Serileştirilecek nesne. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Bu anahtarla ilişkili veri mevcutsa seriden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | java.lang.String | İstenen girdiyi tanımlayan bir anahtar. |
| clazz | java.lang.Class<T> | Beklenen değerin sınıfı. |

**Returns:**
T - bulunan değer ya da null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Dosya adında filtreyi içeren tüm dosya adlarını döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filter | java.lang.String | Kullanılacak filtre. |

**Returns:**
java.util.List<java.lang.String> - Dosya adında filtreyi içeren dosya adları.
