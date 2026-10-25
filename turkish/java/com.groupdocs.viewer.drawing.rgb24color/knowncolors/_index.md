---
title: "KnownColors"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: 
type: docs
weight: 10
url: /tr/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Bir rengin dize adıyla bulunmaya çalışır. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Bir rengin adını RGB değeriyle bulmaya çalışır. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Bir rengin dize adıyla bulunmaya çalışır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | keyword | java.lang.String | Bir renk adı. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Bulunan renk için sonuç kapsayıcısı, başarısızlıkta CssLevel1.Black. |
|

**Returns:**
boolean - Renk isimle başarıyla bulunmuşsa True, aksi takdirde false.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Bir rengin adını RGB değeriyle bulmaya çalışır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Bir renk örneği. |
|
|  | ad | java.lang.String[] | Bulunan renk adının sonuç kapsayıcısı, başarısızlıkta ise null. |
|

**Returns:**
boolean - Verilen renk için ad başarıyla bulunmuşsa true, aksi takdirde false.

