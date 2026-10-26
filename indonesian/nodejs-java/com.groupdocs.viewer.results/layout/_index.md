---
title: "Tata Letak"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili tata letak yang terdapat dalam gambar CAD."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Mewakili tata letak yang terdapat dalam gambar CAD.

Antarmuka Tata Letak mendefinisikan kontrak untuk mengakses dan memanipulasi tata letak dalam gambar CAD pada komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti nama tata letak, dimensi, dan properti lainnya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengambil nama tata letak. |
| [setName(String name)](#setName-java.lang.String-) | Mengatur nama tata letak. |
| [getWidth()](#getWidth--) | Mengambil lebar tata letak. |
| [setWidth(double width)](#setWidth-double-) | Mengatur lebar tata letak. |
| [getHeight()](#getHeight--) | Mengambil tinggi tata letak. |
| [setHeight(double height)](#setHeight-double-) | Mengatur tinggi tata letak. |
| [equals(Object other)](#equals-java.lang.Object-) | Memeriksa apakah objek ini sama dengan objek yang diberikan. |
### getName() {#getName--}
```
public abstract String getName()
```


Mengambil nama tata letak.

**Returns:**
java.lang.String - nama tata letak.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Mengatur nama tata letak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | Nama yang akan diatur untuk tata letak. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Mengambil lebar tata letak.

**Returns:**
double - lebar tata letak.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Mengatur lebar tata letak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | double | Lebar yang akan diatur untuk tata letak. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Mengambil tinggi tata letak.

**Returns:**
double - tinggi tata letak.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Mengatur tinggi tata letak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | double | Tinggi yang akan diatur untuk tata letak. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Memeriksa apakah objek ini sama dengan objek yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lainnya | java.lang.Object | Objek yang akan dibandingkan. |

**Returns:**
boolean -  true  jika objek-objek tersebut sama,  false  jika tidak.
