---
title: "FontSettings"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menyediakan metode untuk bekerja dengan sumber yang mencari font TrueType."
type: docs
weight: 12
url: /id/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Menyediakan metode untuk bekerja dengan sumber yang mencari font TrueType.


Kelas FontSettings digunakan untuk menentukan dan mengelola sumber untuk menemukan font TrueType.
Ini menyediakan metode untuk menambahkan dan mengatur ulang sumber font untuk API GroupDocs.Viewer.


Contoh penggunaan:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Mengatur sumber untuk mencari font TrueType saat merender dokumen. |
|
|  | [resetFontSources()](#resetFontSources--) | Mengatur ulang sumber font yang telah diatur sebelumnya. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Mengatur sumber untuk mencari font TrueType saat merender dokumen.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Sumber font yang akan diatur. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Mengatur ulang sumber font yang telah diatur sebelumnya.


