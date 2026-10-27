---
title: "ImageQuality"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "PDF belgeleri tarafından içerilen çıktı HTML'deki görüntü kalitesi."
type: docs
weight: 41
url: /tr/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF belgeleri tarafından içerilen çıktı HTML'deki görüntü kalitesi.

ImageQuality enum'ı, GroupDocs.Viewer bileşenindeki PDF belgelerinde bulunan çıktı HTML'deki görüntü kalitesini temsil eder. Oluşturulan HTML çıktısındaki görüntülerin işlenmesini ve sıkıştırılmasını kontrol etmek için kullanılabilecek farklı görüntü kalitesi seviyeleri sağlar.

Örnek kullanım:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Açıklama |
| --- | --- |
| [LOW](#LOW) | Kabul edilebilir kalite ve en iyi performans. |
| [MEDIUM](#MEDIUM) | Daha iyi kalite ve daha yavaş performans. |
| [HIGH](#HIGH) | En iyi kalite ancak yavaş performans. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Kabul edilebilir kalite ve en iyi performans. Bu ayar, görüntü kalitesine göre işleme hızını önceliklendirir.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Daha iyi kalite ve daha yavaş performans. Bu ayar, görüntü kalitesi ile işleme hızı arasında bir denge sağlar.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


En iyi kalite ancak yavaş performans. Bu ayar, işleme hızına göre görüntü kalitesini önceliklendirir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
