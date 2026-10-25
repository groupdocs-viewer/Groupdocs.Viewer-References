---
title: "CacheKeys"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Önbellek girdisi için benzersiz tanımlayıcıyı almayı sağlayan yöntemler sunar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Önbellek girdisi için benzersiz tanımlayıcıyı almayı sağlayan yöntemler sunar.


Sınıf, belge yolu, render seçenekleri ve kaynak adı gibi farklı parametrelere göre önbellek anahtarları oluşturmanıza olanak tanır.
Bu önbellek anahtarları, verimli belge render'ı için önbelleğe alınmış verileri depolamak ve geri almak için kullanılabilir.


Örnek kullanım:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Bir [Attachment](../../com.groupdocs.viewer.results/attachment) nesneleri koleksiyonunu temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür. |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Bir ek dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Bir [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır. |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Bir [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır. |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Bir dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Bir sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Bir [Resource](../../com.groupdocs.viewer.results/resource) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür. |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Bir [Resource](../../com.groupdocs.viewer.results/resource) nesnelerini temsil eden önbellek girdilerini aramak için bir filtre dizesi döndürür. |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Bir [Attachment](../../com.groupdocs.viewer.results/attachment) nesneleri koleksiyonunu temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür.


**Returns:**
java.lang.String - ekler önbellek girdisi için benzersiz tanımlayıcı.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Bir ek dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | attachmentId | java.lang.String | Ek'in (tek bir dosya bağlamında) benzersiz tanımlayıcısı. |
|

**Returns:**
java.lang.String - ek dosyası önbellek girdisi için benzersiz tanımlayıcı.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Bir [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır.


**Returns:**
java.lang.String - önbellek girdisi için benzersiz tanımlayıcı.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Bir [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır.


**Returns:**
java.lang.String - bir [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Bir dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extension | java.lang.String | Dosya adı son eki (nokta "." dahil) örn. ".doc". |
|

**Returns:**
java.lang.String - bir dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Bir sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcıyı alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Sayfanın numarası. |
|
|  | extension | java.lang.String | Dosya adı son eki (nokta "." dahil) örn. ".doc". |
|

**Returns:**
java.lang.String - bir sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Bir [Resource](../../com.groupdocs.viewer.results/resource) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcıyı döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Sayfanın numarası. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML kaynağı. |
|

**Returns:**
java.lang.String - önbellek girdisi için benzersiz tanımlayıcı.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Bir [Resource](../../com.groupdocs.viewer.results/resource) nesnelerini temsil eden önbellek girdilerini aramak için bir filtre dizesi döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumber | int | Sayfanın numarası. |
|

**Returns:**
java.lang.String - önbellek girişlerini aramak için kullanılan filtre dizesi.

