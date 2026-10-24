---
title: "Layer"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili lapisan yang terdapat dalam gambar CAD."
type: docs
weight: 16
url: /id/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Mewakili lapisan yang terdapat dalam gambar CAD.


Antarmuka Layer mendefinisikan kontrak untuk mengakses dan memanipulasi lapisan dalam gambar CAD
di komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti nama lapisan,
visibilitas, dan properti lainnya.


Contoh penggunaan:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getName()](#getName--) | Mengambil nama lapisan. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Menetapkan nama lapisan. |
|
|  | [isVisible()](#isVisible--) | Memeriksa visibilitas lapisan. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | Menetapkan visibilitas lapisan. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Memeriksa apakah objek ini sama dengan objek yang diberikan. |
|
### getName() {#getName--}
```
public abstract String getName()
```


Mengambil nama lapisan.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - nama lapisan.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Menetapkan nama lapisan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | nama | java.lang.String | Nama baru untuk lapisan. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Memeriksa visibilitas lapisan.


Lapisan gambar CAD yang dimatikan atau dibekukan tidak terlihat.
Untuk merender lapisan yang tidak terlihat, gunakan opsi [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  jika lapisan terlihat,  false  sebaliknya.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


Menetapkan visibilitas lapisan.


Jika
true
, lapisan akan terlihat; jika
false
, maka akan disembunyikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isVisible | boolean | Apakah lapisan harus terlihat atau tidak. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Memeriksa apakah objek ini sama dengan objek yang diberikan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | lainnya | java.lang.Object | Objek yang akan dibandingkan. |
|

**Returns:**
boolean -  true  jika objek-objek tersebut sama,  false  jika tidak.

