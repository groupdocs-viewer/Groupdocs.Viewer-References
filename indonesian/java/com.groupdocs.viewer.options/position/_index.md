---
title: "Posisi"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mendefinisikan posisi watermark."
type: docs
weight: 43
url: /id/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Mendefinisikan posisi watermark.


Enum Position mewakili berbagai posisi untuk watermark dalam komponen GroupDocs.Viewer.
Ini menyediakan sekumpulan posisi yang telah ditentukan sebelumnya yang dapat digunakan untuk menentukan penempatan watermark
pada dokumen atau gambar selama proses rendering.


Contoh penggunaan:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | Posisi diagonal. |
|
|  | [TOP_LEFT](#TOP-LEFT) | Posisi kiri atas. |
|
|  | [TOP_CENTER](#TOP-CENTER) | Posisi tengah atas. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | Posisi kanan atas. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | Posisi kiri bawah. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | Posisi tengah bawah. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Posisi kanan bawah. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Posisi diagonal.
Posisi ini mewakili penyelarasan atau penempatan diagonal.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Posisi kiri atas.
Posisi ini mewakili penyelarasan atau penempatan sudut kiri atas.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Posisi tengah atas.
Posisi ini mewakili penyelarasan atau penempatan tengah atas.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Posisi kanan atas.
Posisi ini mewakili penyelarasan atau penempatan sudut kanan atas.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Posisi kiri bawah.
Posisi ini mewakili penyelarasan atau penempatan sudut kiri bawah.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Posisi tengah bawah.
Posisi ini mewakili penyelarasan atau penempatan tengah bawah.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Posisi kanan bawah.
Posisi ini mewakili penyelarasan atau penempatan sudut kanan bawah.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
