---
title: "Position"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحدد موضع العلامة المائية."
type: docs
weight: 43
url: /ar/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

يحدد موضع العلامة المائية.


تعداد Position يمثل مواقع مختلفة للعلامة المائية في مكوّن GroupDocs.Viewer.
يوفر مجموعة من المواقع المحددة مسبقًا التي يمكن استخدامها لتحديد وضع العلامة المائية.
على مستند أو صورة أثناء عملية العرض.


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


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | الموضع القطري. |
|
|  | [TOP_LEFT](#TOP-LEFT) | الموضع العلوي الأيسر. |
|
|  | [TOP_CENTER](#TOP-CENTER) | الموضع العلوي المركزي. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | الموضع العلوي الأيمن. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | الموضع السفلي الأيسر. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | الموضع السفلي المركزي. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | الموضع السفلي الأيمن. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


الموضع القطري.
هذا الموضع يمثل محاذاة أو وضعًا قطريًا.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


الموضع العلوي الأيسر.
هذا الموضع يمثل محاذاة أو وضع الزاوية العلوية اليسرى.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


الموضع العلوي المركزي.
هذا الموضع يمثل محاذاة أو وضع المركز العلوي.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


الموضع العلوي الأيمن.
هذا الموضع يمثل محاذاة أو وضع الزاوية العلوية اليمنى.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


الموضع السفلي الأيسر.
هذا الموضع يمثل محاذاة أو وضع الزاوية السفلية اليسرى.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


الموضع السفلي المركزي.
هذا الموضع يمثل محاذاة أو وضع المركز السفلي.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


الموضع السفلي الأيمن.
هذا الموضع يمثل محاذاة أو وضع الزاوية السفلية اليمنى.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
