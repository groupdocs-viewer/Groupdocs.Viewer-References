---
title: "ViewerSettings"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku komponen Viewer."
type: docs
weight: 13
url: /id/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Mendefinisikan pengaturan untuk menyesuaikan perilaku komponen Viewer.


Kelas ViewerSettings menyediakan opsi dan properti untuk menyesuaikan perilaku komponen GroupDocs.Viewer selama proses rendering dokumen.
Anda dapat menggunakan kelas ini untuk menentukan berbagai pengaturan, seperti logger, implementasi cache khusus, dan lainnya.


Contoh penggunaan:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Menginisialisasi instance baru dari |
ViewerSettings
kelas.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Menginisialisasi instance baru dari |
ViewerSettings
kelas.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Menginisialisasi instance baru dari |
ViewerSettings
kelas.
|
|  | [ViewerSettings()](#ViewerSettings--) | Menginisialisasi instance baru dari |
ViewerSettings
kelas.
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLogger()](#getLogger--) | Mendapatkan implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Mengatur implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak). |
|
|  | [getCache()](#getCache--) | Mendapatkan implementasi cache yang digunakan untuk menyimpan hasil rendering. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Mengatur implementasi cache yang digunakan untuk menyimpan hasil rendering. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Menginisialisasi instance baru dari
ViewerSettings
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Cache. |
|
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Menginisialisasi instance baru dari
ViewerSettings
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Logger. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Menginisialisasi instance baru dari
ViewerSettings
kelas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Cache. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Menginisialisasi instance baru dari
ViewerSettings
kelas.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Mendapatkan implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak).


**Returns:**
com.groupdocs.foundation.logging.ILogger - implementasi logger.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Mengatur implementasi logger yang digunakan untuk pencatatan (Kesalahan, Peringatan, Jejak).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | Implementasi logger yang akan diatur. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Mendapatkan implementasi cache yang digunakan untuk menyimpan hasil rendering.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Mengatur implementasi cache yang digunakan untuk menyimpan hasil rendering.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Implementasi cache. |
|

