---
title: "TextOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Metin dosyalarının sayfalara bölünme seçenekleri."
type: docs
weight: 32
url: /tr/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Metin dosyalarının sayfalara bölünme seçenekleri.

TextOptions sınıfı, GroupDocs.Viewer bileşeninde metin dosyalarını sayfalara bölmek için seçenekler sunar. Metin dosyalarının renderleme ve görüntüleme amacıyla bireysel sayfalara nasıl bölüneceğini kontrol etmenizi sağlar.

Örnek kullanım:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextOptions()](#TextOptions--) | TextOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Bir sayfadaki satır başına maksimum karakter sayısını alır. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Bir sayfadaki satır başına maksimum karakter sayısını ayarlar. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Bir sayfadaki maksimum satır sayısını alır. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Bir sayfadaki maksimum satır sayısını ayarlar. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


TextOptions sınıfının yeni bir örneğini başlatır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Bir sayfadaki satır başına maksimum karakter sayısını alır.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - bir sayfadaki satır başına maksimum karakter sayısı.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Bir sayfadaki satır başına maksimum karakter sayısını ayarlar.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxCharsPerRow | int | Bir sayfadaki satır başına maksimum karakter sayısı. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Bir sayfadaki maksimum satır sayısını alır.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - maksimum satır sayısı.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Bir sayfadaki maksimum satır sayısını ayarlar.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxRowsPerPage | int | Maksimum satır sayısı. |

