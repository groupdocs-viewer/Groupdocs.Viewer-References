---
title: "Position"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحدد موضع العلامة المائية."
type: docs
weight: 43
url: /ar/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

يحدد موضع العلامة المائية.

عدد Position يمثل مواقع مختلفة لعلامة مائية في مكوّن GroupDocs.Viewer. يوفر مجموعة من المواقع المحددة مسبقًا التي يمكن استخدامها لتحديد موضع العلامة المائية على مستند أو صورة أثناء عملية العرض.

مثال على الاستخدام:

```

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
 
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | الموضع القطري. |
| [TOP_LEFT](#TOP-LEFT) | الموضع العلوي الأيسر. |
| [TOP_CENTER](#TOP-CENTER) | الموضع العلوي الأوسط. |
| [TOP_RIGHT](#TOP-RIGHT) | الموضع العلوي الأيمن. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | الموضع السفلي الأيسر. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | الموضع السفلي الأوسط. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | الموضع السفلي الأيمن. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


الموضع القطري. يمثل هذا الموضع محاذاة أو وضعًا قطريًا.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


الموضع العلوي الأيسر. يمثل هذا الموضع محاذاة أو وضعًا في الزاوية العلوية اليسرى.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


الموضع العلوي الأوسط. يمثل هذا الموضع محاذاة أو وضعًا في الجزء العلوي الأوسط.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


الموضع العلوي الأيمن. يمثل هذا الموضع محاذاة أو وضعًا في الزاوية العلوية اليمنى.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


الموضع السفلي الأيسر. يمثل هذا الموضع محاذاة أو وضعًا في الزاوية السفلية اليسرى.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


الموضع السفلي الأوسط. يمثل هذا الموضع محاذاة أو وضعًا في الجزء السفلي الأوسط.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


الموضع السفلي الأيمن. يمثل هذا الموضع محاذاة أو وضعًا في الزاوية السفلية اليمنى.

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
| الاسم | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
