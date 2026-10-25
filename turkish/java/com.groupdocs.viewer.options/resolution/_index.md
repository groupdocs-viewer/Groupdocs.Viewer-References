---
title: "Çözünürlük"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Görüntüler ve çıktı belgesi için çözünürlüğü ayarlama seçeneği sağlar."
type: docs
weight: 44
url: /tr/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

Görüntüler için çözünürlük ayarlama seçeneği sağlar: çıktı belgesi.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [DPI_330](#DPI-330) | Yüksek çözünürlüklü (HD) ekranlar için iyi kalite. |
|
|  | [DPI_220](#DPI-220) | Çoğu yazıcı ve ekranda mükemmel kalite. |
|
|  | [DPI_150](#DPI-150) | Web sayfaları ve projektörler için iyidir. |
|
|  | [DPI_96](#DPI-96) | Web sayfaları ve projektörler için iyidir. |
|
|  | [DPI_72](#DPI-72) | Varsayılan sıkıştırma seviyesi. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | Varsayılan sıkıştırma seviyesi - belgeye göre. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | Kalite DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | Aspose.Slides resim çözünürlüğünü seçenekler Resolution sınıfından alın. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


Yüksek çözünürlüklü (HD) ekranlar için iyi kalite.


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


Çoğu yazıcı ve ekranda mükemmel kalite.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


Web sayfaları ve projektörler için iyidir.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


Web sayfaları ve projektörler için iyidir.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


Varsayılan sıkıştırma seviyesi.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


Varsayılan sıkıştırma seviyesi - belgeye göre.


### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


Kalite DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


Aspose.Slides resim çözünürlüğünü seçenekler Resolution sınıfından alın.


**Returns:**
int
