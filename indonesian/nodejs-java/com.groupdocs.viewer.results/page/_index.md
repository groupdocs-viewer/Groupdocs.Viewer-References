---
title: "Halaman"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili satu halaman yang dapat dilihat."
type: docs
weight: 21
url: /id/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Mewakili satu halaman yang dapat dilihat.

Antarmuka Page mendefinisikan kontrak untuk mengakses dan memanipulasi satu halaman yang dapat dilihat dalam komponen GroupDocs.Viewer. Ini menyediakan metode untuk mengambil informasi seperti nomor halaman, ukuran, dan properti lainnya.

Contoh penggunaan:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengambil nama lembar kerja atau halaman. |
| [setName(String name)](#setName-java.lang.String-) | Menetapkan nama lembar kerja atau halaman. |
| [getNumber()](#getNumber--) | Mengambil nomor halaman. |
| [setNumber(int number)](#setNumber-int-) | Menetapkan nomor halaman. |
| [isVisible()](#isVisible--) | Mengambil indikator visibilitas halaman. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Menetapkan indikator visibilitas halaman. |
| [getWidth()](#getWidth--) | Mengambil lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| [setWidth(int width)](#setWidth-int-) | Menetapkan lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| [getHeight()](#getHeight--) | Mengambil tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| [setHeight(int height)](#setHeight-int-) | Menetapkan tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG. |
| [getLines()](#getLines--) | Mengambil baris yang terdapat dalam halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Menetapkan baris yang terdapat dalam halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan. |
### getName() {#getName--}
```
public abstract String getName()
```


Mengambil nama lembar kerja atau halaman.

**Returns:**
java.lang.String - nama lembar kerja atau halaman.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Menetapkan nama lembar kerja atau halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String | nama yang akan ditetapkan untuk lembar kerja atau halaman. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Mengambil nomor halaman.

**Returns:**
int - nomor halaman.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Menetapkan nomor halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| number | int | nomor halaman yang akan ditetapkan. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Mengambil indikator visibilitas halaman.

**Returns:**
boolean - indikator visibilitas halaman.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Menetapkan indikator visibilitas halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| terlihat | boolean | true jika halaman terlihat, false sebaliknya. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Mengambil lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG.

**Returns:**
int - lebar halaman.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Menetapkan lebar halaman dalam piksel saat ditampilkan sebagai JPG atau PNG.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | lebar yang akan diatur untuk halaman. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Mengambil tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG.

**Returns:**
int - tinggi halaman.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Menetapkan tinggi halaman dalam piksel saat ditampilkan sebagai JPG atau PNG.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | int | tinggi yang akan diatur untuk halaman. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Mengambil baris yang terdapat dalam halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - baris-baris yang terdapat dalam halaman.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Menetapkan baris yang terdapat dalam halaman saat ditampilkan sebagai JPG atau PNG dengan Ekstraksi Teks diaktifkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | daftar baris yang akan diatur untuk halaman. |

