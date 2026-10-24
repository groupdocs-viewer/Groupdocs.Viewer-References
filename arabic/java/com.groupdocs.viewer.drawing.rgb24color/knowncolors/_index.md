---
title: "KnownColors"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: 
type: docs
weight: 10
url: /ar/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | يحاول العثور على لون عبر اسمه النصي. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | يحاول العثور على اسم اللون عبر قيمته RGB. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


يحاول العثور على لون عبر اسمه النصي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة مفتاح | java.lang.String | اسم لون. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | حاوية النتيجة للون المكتشف، أو CssLevel1.Black في حالة الفشل. |
|

**Returns:**
منطقي - True إذا تم العثور على اللون بنجاح بالاسم، false خلاف ذلك.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


يحاول العثور على اسم اللون عبر قيمته RGB.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | مثال لون. |
|
|  | name | java.lang.String[] | حاوية النتيجة لاسم اللون المكتشف، أو null في حالة الفشل. |
|

**Returns:**
منطقي - True إذا تم العثور على الاسم بنجاح للون المعطى، false خلاف ذلك.

