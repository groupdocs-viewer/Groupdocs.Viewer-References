---
title: "Size"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على حجم العلامة المائية."
type: docs
weight: 30
url: /ar/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

يحتوي على حجم العلامة المائية.


تمثل الفئة Size حجم العلامة المائية في مكوّن GroupDocs.Viewer.
توفر خيارات لتحديد أبعاد العلامة المائية، مثل العرض والارتفاع.


مثال على الاستخدام:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | ينشئ مثلاً جديداً من |
Size
الفئة.
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | يمثل الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة. |
|
|  | [HALF_SIZE](#HALF-SIZE) | يمثل نصف الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة. |
|
|  | [ONE_THIRD](#ONE-THIRD) | يمثل ثلث الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | يعيد حجم نص العلامة المائية كنسبة مئوية بالنسبة إلى عرض الصفحة. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


ينشئ مثلاً جديداً من
Size
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | relativeSize | byte | الحجم كنسبة مئوية بالنسبة إلى حجم الصفحة. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


يمثل الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


يمثل نصف الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


يمثل ثلث الحد الأقصى لحجم نص العلامة المائية الذي يتناسب مع الصفحة.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


يعيد حجم نص العلامة المائية كنسبة مئوية بالنسبة إلى عرض الصفحة.


**Returns:**
byte - حجم نص العلامة المائية كنسبة مئوية.

