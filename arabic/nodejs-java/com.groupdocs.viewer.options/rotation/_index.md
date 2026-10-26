---
title: "التدوير"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحتوي على تدوير الصفحة بالدرجات باتجاه عقارب الساعة."
type: docs
weight: 45
url: /ar/nodejs-java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

يحتوي على دوران الصفحة بالدرجات (مع اتجاه عقارب الساعة).

يمثل تعداد Rotation زوايا تدوير مختلفة للصفحة في مكوّن GroupDocs.Viewer. يوفر مجموعة من خيارات التدوير المحددة مسبقًا التي يمكن استخدامها لتحديد زاوية التدوير عند عرض صفحة في سيناريوهات مختلفة لعرض المستندات أو تحويلها.

مثال على الاستخدام:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [ON_90_DEGREE](#ON-90-DEGREE) | تدوير الصفحة بزاوية 90 درجة. |
| [ON_180_DEGREE](#ON-180-DEGREE) | تدوير الصفحة بزاوية 180 درجة. |
| [ON_270_DEGREE](#ON-270-DEGREE) | تدوير الصفحة بزاوية 270 درجة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


تدوير الصفحة بزاوية 90 درجة. يمثل هذا التدوير تدوير الصفحة بزاوية 90 درجة باتجاه عقارب الساعة.

### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


تدوير الصفحة بزاوية 180 درجة. يمثل هذا التدوير تدوير الصفحة بزاوية 180 درجة باتجاه عقارب الساعة.

### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


تدوير الصفحة بزاوية 270 درجة. يمثل هذا التدوير تدوير الصفحة بزاوية 270 درجة باتجاه عقارب الساعة.

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
| الاسم | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
