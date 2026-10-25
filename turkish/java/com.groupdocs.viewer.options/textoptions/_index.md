---
title: "TextOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Metin dosyalarının sayfalara bölünme seçenekleri."
type: docs
weight: 32
url: /tr/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Metin dosyalarının sayfalara bölünme seçenekleri.


TextOptions sınıfı, GroupDocs.Viewer bileşeninde metin dosyalarını sayfalara bölmek için seçenekler sağlar.
Metin dosyalarının işleme ve görüntüleme amacıyla tek tek sayfalara nasıl bölüneceğini kontrol etmenizi sağlar.


Örnek kullanım:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | Yeni bir örnek başlatır |
TextOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Bir sayfadaki satır başına azami karakter sayısını alır. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Bir sayfadaki satır başına azami karakter sayısını ayarlar. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Bir sayfadaki azami satır sayısını alır. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Bir sayfadaki azami satır sayısını ayarlar. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Yeni bir örnek başlatır
TextOptions
sınıf.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) bakın.


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Bir sayfadaki satır başına azami karakter sayısını alır.


***Note:** The default value is 85.*
Varsayılan değer 85'tir. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) bakın.


**Returns:**
int - bir sayfadaki satır başına azami karakter sayısı.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Bir sayfadaki satır başına azami karakter sayısını ayarlar.


***Note:** The default value is 85.*
Varsayılan değer 85'tir. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxCharsPerRow | int | Bir sayfadaki satır başına azami karakter sayısı. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Bir sayfadaki azami satır sayısını alır.


***Note:** The default value is 55.*
Varsayılan değer 55'tir. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) bakın.


**Returns:**
int - azami satır sayısı.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Bir sayfadaki azami satır sayısını ayarlar.


***Note:** The default value is 55.*
Varsayılan değer 55'tir. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxRowsPerPage | int | Azami satır sayısı. |
|

