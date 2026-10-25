---
title: "Size"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Filigran boyutunu içerir."
type: docs
weight: 30
url: /tr/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Filigran boyutunu içerir.


Size sınıfı, GroupDocs.Viewer bileşenindeki bir filigranın boyutunu temsil eder.
Filigranın genişlik ve yükseklik gibi boyutlarını belirtmek için seçenekler sunar.


Örnek kullanım:

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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Yeni bir örnek başlatır |
Size
sınıf.
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Sayfaya sığan filigran metninin maksimum boyutunu temsil eder. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Sayfaya sığan filigran metninin maksimum boyutunun yarısını temsil eder. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Sayfaya sığan filigran metninin maksimum boyutunun üçte birini temsil eder. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Filigran metin boyutunu sayfa genişliğine oranla yüzde olarak döndürür. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Yeni bir örnek başlatır
Size
sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | relativeSize | byte | Sayfa boyutuna oranla yüzde olarak boyut. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Sayfaya sığan filigran metninin maksimum boyutunu temsil eder.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Sayfaya sığan filigran metninin maksimum boyutunun yarısını temsil eder.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Sayfaya sığan filigran metninin maksimum boyutunun üçte birini temsil eder.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Filigran metin boyutunu sayfa genişliğine oranla yüzde olarak döndürür.


**Returns:**
byte - filigran metin boyutu yüzde olarak.

