---
title: "KnownColors"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: 
type: docs
weight: 10
url: /id/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Mencoba menemukan warna berdasarkan nama string-nya. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Mencoba menemukan nama warna berdasarkan nilai RGB-nya. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Mencoba menemukan warna berdasarkan nama string-nya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kata kunci | java.lang.String | Sebuah nama warna. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Kontainer hasil untuk warna yang ditemukan, atau CssLevel1.Black jika gagal. |
|

**Returns:**
boolean - True jika warna berhasil ditemukan berdasarkan nama, false jika tidak.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Mencoba menemukan nama warna berdasarkan nilai RGB-nya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Sebuah instance warna. |
|
|  | nama | java.lang.String[] | Kontainer hasil untuk nama warna yang ditemukan, atau null jika gagal. |
|

**Returns:**
boolean - True jika nama berhasil ditemukan untuk warna yang diberikan, false jika tidak.

