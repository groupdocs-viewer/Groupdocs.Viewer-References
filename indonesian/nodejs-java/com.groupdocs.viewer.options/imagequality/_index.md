---
title: "ImageQuality"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Kualitas gambar dalam HTML output yang terdapat dalam dokumen PDF."
type: docs
weight: 41
url: /id/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Kualitas gambar dalam HTML output yang terdapat dalam dokumen PDF.

Enum ImageQuality mewakili kualitas gambar dalam HTML output yang terdapat dalam dokumen PDF pada komponen GroupDocs.Viewer. Enum ini menyediakan tingkat kualitas gambar yang berbeda yang dapat digunakan untuk mengontrol rendering dan kompresi gambar dalam output HTML yang dihasilkan.

Contoh penggunaan:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [LOW](#LOW) | Kualitas yang dapat diterima dan kinerja terbaik. |
| [MEDIUM](#MEDIUM) | Kualitas lebih baik dan kinerja lebih lambat. |
| [HIGH](#HIGH) | Kualitas terbaik tetapi kinerja lambat. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Kualitas yang dapat diterima dan kinerja terbaik. Pengaturan ini memprioritaskan kecepatan rendering dibandingkan kualitas gambar.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Kualitas lebih baik dan kinerja lebih lambat. Pengaturan ini memberikan keseimbangan antara kualitas gambar dan kecepatan rendering.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Kualitas terbaik tetapi kinerja lambat. Pengaturan ini memprioritaskan kualitas gambar dibandingkan kecepatan rendering.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
