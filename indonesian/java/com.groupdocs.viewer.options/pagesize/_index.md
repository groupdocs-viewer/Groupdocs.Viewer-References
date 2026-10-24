---
title: "PageSize"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Ukuran halaman."
type: docs
weight: 42
url: /id/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Ukuran halaman.


Enum PageSize mewakili berbagai ukuran halaman dalam komponen GroupDocs.Viewer.
Ini menyediakan sekumpulan ukuran halaman pra‑definisi yang dapat digunakan untuk menentukan dimensi
dari sebuah halaman dalam berbagai skenario rendering dokumen.


Contoh penggunaan:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | Ukuran halaman default, tidak ditentukan. |
|
|  | [LETTER](#LETTER) | Ukuran halaman Letter dalam poin adalah 792 x 612. |
|
|  | [LEDGER](#LEDGER) | Ukuran halaman A0 dalam poin adalah 3371 x 2384. |
|
|  | [A0](#A0) | Ukuran halaman A1 dalam poin adalah 2384 x 1685. |
|
|  | [A1](#A1) | Ukuran halaman A2 dalam poin adalah 1684 x 1190. |
|
|  | [A2](#A2) | Ukuran halaman A3 dalam poin adalah 1190 x 842. |
|
|  | [A3](#A3) | Ukuran halaman A3 dalam poin adalah 1190 x 842. |
|
|  | [A4](#A4) | Ukuran halaman A4 dalam poin adalah 842 x 595. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Ukuran halaman default, tidak ditentukan.
Ukuran ini digunakan ketika tidak ada ukuran halaman spesifik yang ditentukan.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Ukuran halaman Letter dalam poin adalah 792 x 612.
Ukuran halaman ini biasanya digunakan untuk surat dan dokumen di Amerika Utara.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


Ukuran halaman A0 dalam poin adalah 3371 x 2384.
Ukuran halaman besar ini merupakan bagian dari standar internasional ISO 216.


### A0 {#A0}
```
public static final PageSize A0
```


Ukuran halaman A1 dalam poin adalah 2384 x 1685.
Ukuran halaman ini merupakan bagian dari standar internasional ISO 216.


### A1 {#A1}
```
public static final PageSize A1
```


Ukuran halaman A2 dalam poin adalah 1684 x 1190.
Ukuran halaman ini merupakan bagian dari standar internasional ISO 216.


### A2 {#A2}
```
public static final PageSize A2
```


Ukuran halaman A3 dalam poin adalah 1190 x 842.
Ukuran halaman ini merupakan bagian dari standar internasional ISO 216.


### A3 {#A3}
```
public static final PageSize A3
```


Ukuran halaman A3 dalam poin adalah 1190 x 842.
Ukuran halaman ini merupakan bagian dari standar internasional ISO 216.


### A4 {#A4}
```
public static final PageSize A4
```


Ukuran halaman A4 dalam poin adalah 842 x 595.
Ukuran halaman ini merupakan bagian dari standar internasional ISO 216.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
