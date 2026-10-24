---
title: "Rotation"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Berisi rotasi halaman dalam derajat searah jarum jam."
type: docs
weight: 45
url: /id/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Mengandung rotasi halaman dalam derajat (searah jarum jam).


Enum Rotation mewakili berbagai sudut rotasi untuk sebuah halaman dalam komponen GroupDocs.Viewer.
Ini menyediakan sekumpulan opsi rotasi yang telah ditentukan sebelumnya yang dapat digunakan untuk menentukan sudut rotasi
untuk merender halaman dalam berbagai skenario penampilan atau konversi dokumen.


Contoh penggunaan:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | Rotasi halaman 90 derajat. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | Rotasi halaman 180 derajat. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | Rotasi halaman 270 derajat. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


Rotasi halaman 90 derajat.
Rotasi ini mewakili rotasi halaman 90 derajat searah jarum jam.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


Rotasi halaman 180 derajat.
Rotasi ini mewakili rotasi halaman 180 derajat searah jarum jam.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


Rotasi halaman 270 derajat.
Rotasi ini mewakili rotasi halaman 270 derajat searah jarum jam.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
