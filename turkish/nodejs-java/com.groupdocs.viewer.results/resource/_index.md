---
title: "Resource"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Yazı tipi, stil, resim veya grafik gibi HTML kaynağını temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Yazı tipi, stil, resim veya grafik gibi HTML kaynağını temsil eder.

Resource sınıfı, GroupDocs.Viewer bileşeninde HTML render'ında kullanılan bir kaynağı temsil eder. Oluşturulan HTML çıktısında render süreci sırasında dahil edilen veya başvurulan, yazı tipleri, stiller, resimler veya grafikler gibi çeşitli kaynak türlerini temsil edebilir.

Örnek kullanım:

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Resource sınıfının yeni bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileName()](#getFileName--) | Kaynağın dosya adını döndürür. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Kaynağın dosya adını ayarlar. |
| [isNested()](#isNested--) | Kaynağın başka bir kaynağın içinde bulunup bulunmadığını döndürür, ör. bir CSS veya SVG kaynağında bulunan bir yazı tipi kaynağı. |
| [setNested(boolean nested)](#setNested-boolean-) | Kaynağın başka bir kaynağın içinde bulunup bulunmadığını ayarlar. |
| [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Resource sınıfının yeni bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Kaynak dosya adı. |
| iç içe | boolean | Kaynağın başka bir kaynağın içinde bulunup bulunmadığını gösterir, ör. bir CSS veya SVG kaynağında bulunan bir yazı tipi kaynağı. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Kaynağın dosya adını döndürür.

**Returns:**
java.lang.String - kaynağın dosya adı.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Kaynağın dosya adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Kaynak için yeni dosya adı. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Kaynağın başka bir kaynağın içinde bulunup bulunmadığını döndürür, ör. bir CSS veya SVG kaynağında bulunan bir yazı tipi kaynağı.

**Returns:**
boolean - Kaynağın başka bir kaynağın içinde bulunup bulunmadığı.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Kaynağın başka bir kaynağın içinde bulunup bulunmadığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| iç içe | boolean | Kaynağın iç içe olarak ayarlanıp ayarlanmayacağı. |

### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - mevcut nesnenin dize temsili.
