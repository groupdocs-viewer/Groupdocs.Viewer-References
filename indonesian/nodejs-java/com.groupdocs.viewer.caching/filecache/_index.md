---
title: "FileCache"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili cache lokal di disk."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Mewakili cache lokal di disk.

Kelas FileCache mewakili cache lokal pada disk dalam komponen GroupDocs.Viewer. Ini menyediakan fungsionalitas untuk menyimpan dan mengambil data yang di-cache pada disk untuk rendering dokumen yang efisien.

Contoh penggunaan:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Untuk menggunakan FileCache, Anda perlu membuat instance dari kelas ini dan memberikannya ke objek ViewerSettings. Objek Viewer kemudian akan menggunakan FileCache untuk tujuan caching saat merender dokumen.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Membuat instance baru dari kelas FileCache. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Membuat instance baru dari kelas FileCache. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Membuat instance baru dari kelas FileCache. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Membuat instance baru dari kelas FileCache. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCachePath()](#getCachePath--) | Mendapatkan jalur relatif atau absolut ke folder cache. |
| [getCacheSubFolder()](#getCacheSubFolder--) | Sub-folder yang akan ditambahkan ke jalur cache. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Menyerialkan data ke disk lokal. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Mendeserialkan data yang terkait dengan kunci ini jika ada. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Mengembalikan semua nama file yang mengandung filter dalam nama file. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Membuat instance baru dari kelas FileCache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cachePath | java.lang.String | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Membuat instance baru dari kelas FileCache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Membuat instance baru dari kelas FileCache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cachePath | java.lang.String | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |
| cacheSubFolder | java.lang.String | Sub-folder yang akan ditambahkan ke cachePath. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Membuat instance baru dari kelas FileCache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |
| cacheSubFolder | java.lang.String | Sub-folder yang akan ditambahkan ke cachePath. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Mendapatkan jalur relatif atau absolut ke folder cache.

**Returns:**
java.lang.String - Jalur ke folder cache.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Sub-folder yang akan ditambahkan ke jalur cache.

**Returns:**
java.lang.String - sub-folder yang akan ditambahkan.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Menyerialkan data ke disk lokal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Pengidentifikasi unik untuk entri cache. |
| value | java.lang.Object | Objek yang akan diserialkan. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Mendeserialkan data yang terkait dengan kunci ini jika ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key | java.lang.String | Kunci yang mengidentifikasi entri yang diminta. |
| clazz | java.lang.Class<T> | Kelas dari nilai yang diharapkan. |

**Returns:**
T - nilai yang ditemukan atau null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Mengembalikan semua nama file yang mengandung filter dalam nama file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filter | java.lang.String | Filter yang akan digunakan. |

**Returns:**
java.util.List<java.lang.String> - Nama file yang mengandung filter dalam nama file.
