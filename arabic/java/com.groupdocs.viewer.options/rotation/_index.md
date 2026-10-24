---
title: "Rotation"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على دوران الصفحة بالدرجات في اتجاه عقارب الساعة."
type: docs
weight: 45
url: /ar/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

يحتوي على دوران الصفحة بالدرجات (مع اتجاه عقارب الساعة).


تعداد Rotation يمثل زوايا دوران مختلفة لصفحة في مكوّن GroupDocs.Viewer.
يوفر مجموعة من خيارات الدوران المحددة مسبقًا التي يمكن استخدامها لتحديد زاوية الدوران
لعرض صفحة في سيناريوهات مختلفة لعرض المستندات أو التحويل.


مثال على الاستخدام:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | دوران الصفحة 90 درجة. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | دوران الصفحة 180 درجة. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | دوران الصفحة 270 درجة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


دوران الصفحة 90 درجة.
يمثل هذا الدوران دوران الصفحة 90 درجة في اتجاه عقارب الساعة.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


دوران الصفحة 180 درجة.
يمثل هذا الدوران دوران الصفحة 180 درجة في اتجاه عقارب الساعة.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


دوران الصفحة 270 درجة.
يمثل هذا الدوران دوران الصفحة 270 درجة في اتجاه عقارب الساعة.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
