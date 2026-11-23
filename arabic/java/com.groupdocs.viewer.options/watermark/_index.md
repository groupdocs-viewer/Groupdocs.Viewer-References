---
title: "Watermark"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل علامة مائية نصية."
type: docs
weight: 37
url: /ar/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

يمثل علامة مائية نصية. للحصول على تفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


تمثل فئة Watermark علامة مائية نصية في مكوّن GroupDocs.Viewer.
يُستخدم لتعريف وتطبيق علامة مائية على المخرجات المُصوَّرة للمستندات.


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
|  | [Watermark(String text)](#Watermark-java.lang.String-) | ينشئ مثلاً جديداً من |
Watermark
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | يعيد نص العلامة المائية. |
|
|  | [getColor()](#getColor--) | يعيد لون العلامة المائية. |
|
|  | [getColorAsHex()](#getColorAsHex--) | يعيد لون العلامة المائية بصيغة سداسية عشرية. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | يضبط لون العلامة المائية. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | يضبط لون العلامة المائية. |
|
|  | [getPosition()](#getPosition--) | يعيد موضع العلامة المائية. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | يضبط موضع العلامة المائية. |
|
|  | [getSize()](#getSize--) | يعيد حجم العلامة المائية. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | يضبط حجم العلامة المائية. |
|
|  | [getFontName()](#getFontName--) | يعيد اسم الخط المستخدم للعلامة المائية. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | يضبط اسم الخط المستخدم للعلامة المائية. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


ينشئ مثلاً جديداً من
Watermark
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص العلامة المائية. |
|

### getText() {#getText--}
```
public final String getText()
```


يعيد نص العلامة المائية.
تسترجع هذه الطريقة نص العلامة المائية المطبقة على المستند.


**Returns:**
java.lang.String - نص العلامة المائية.

### getColor() {#getColor--}
```
public final Color getColor()
```


يعيد لون العلامة المائية.
تسترجع هذه الطريقة لون العلامة المائية المطبقة على المستند.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - لون العلامة المائية.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


يعيد لون العلامة المائية بصيغة سداسية عشرية.
تسترجع هذه الطريقة لون العلامة المائية المطبقة على المستند.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - لون العلامة المائية بصيغة سداسية عشرية.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


يضبط لون العلامة المائية.
تضبط هذه الطريقة لون العلامة المائية المطبقة على المستند.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.awt.Color | لون العلامة المائية المراد ضبطه. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


يضبط لون العلامة المائية.
تضبط هذه الطريقة لون العلامة المائية المطبقة على المستند.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | colorName | java.lang.String | لون العلامة المائية المراد ضبطه. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


يعيد موضع العلامة المائية.
تُعيد هذه الطريقة موضع العلامة المائية المطبقة على المستند.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


يضبط موضع العلامة المائية.
تضبط هذه الطريقة موضع العلامة المائية المطبقة على المستند.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | موضع العلامة المائية. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


يعيد حجم العلامة المائية.
تسترجع هذه الطريقة حجم العلامة المائية المطبقة على المستند.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


يضبط حجم العلامة المائية.
تضبط هذه الطريقة حجم العلامة المائية التي ستُطبق على المستند.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | حجم العلامة المائية. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


يعيد اسم الخط المستخدم للعلامة المائية.


**Returns:**
java.lang.String - اسم الخط المستخدم للعلامة المائية.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


يضبط اسم الخط المستخدم للعلامة المائية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الخط المستخدم للعلامة المائية. |
|

