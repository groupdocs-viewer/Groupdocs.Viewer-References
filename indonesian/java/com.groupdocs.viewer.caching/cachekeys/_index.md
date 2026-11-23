---
title: "CacheKeys"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan metode untuk mengambil pengidentifikasi unik untuk entri cache."
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Menyediakan metode untuk mengambil pengidentifikasi unik untuk entri cache.


Kelas ini memungkinkan Anda menghasilkan kunci cache berdasarkan berbagai parameter, seperti jalur dokumen, opsi rendering, dan nama sumber daya.
Kunci cache ini dapat digunakan untuk menyimpan dan mengambil data yang di-cache untuk rendering dokumen yang efisien.


Contoh penggunaan:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili kumpulan objek [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Mengambil pengidentifikasi unik untuk entri cache yang mewakili file lampiran. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Mengambil pengidentifikasi unik untuk entri cache yang mewakili objek [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Mengambil pengidentifikasi unik untuk entri cache yang mewakili objek [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Mengambil pengidentifikasi unik untuk entri cache yang mewakili sebuah file. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Mengambil pengidentifikasi unik untuk entri cache yang mewakili file halaman. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili objek [Resource](../../com.groupdocs.viewer.results/resource). |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Mengembalikan string filter untuk mencari entri cache yang mewakili objek [Resource](../../com.groupdocs.viewer.results/resource). |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili kumpulan objek [Attachment](../../com.groupdocs.viewer.results/attachment).


**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache lampiran.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Mengambil pengidentifikasi unik untuk entri cache yang mewakili file lampiran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | attachmentId | java.lang.String | Pengidentifikasi unik dari lampiran (dalam konteks satu file). |
|

**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache file lampiran.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Mengambil pengidentifikasi unik untuk entri cache yang mewakili objek [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Mengambil pengidentifikasi unik untuk entri cache yang mewakili objek [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache yang mewakili objek [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Mengambil pengidentifikasi unik untuk entri cache yang mewakili sebuah file.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | ekstensi | java.lang.String | Akhiran nama file (termasuk titik ".") misalnya ".doc". |
|

**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache yang mewakili sebuah file.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Mengambil pengidentifikasi unik untuk entri cache yang mewakili file halaman.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumber | int | Nomor halaman. |
|
|  | ekstensi | java.lang.String | Akhiran nama file (termasuk titik ".") misalnya ".doc". |
|

**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache yang mewakili file halaman.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili objek [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumber | int | Nomor halaman. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | Sumber daya HTML. |
|

**Returns:**
java.lang.String - pengidentifikasi unik untuk entri cache.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Mengembalikan string filter untuk mencari entri cache yang mewakili objek [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pageNumber | int | Nomor halaman. |
|

**Returns:**
java.lang.String - string filter untuk mencari entri cache.

