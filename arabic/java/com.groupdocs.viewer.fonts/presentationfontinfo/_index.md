---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يغلف البيانات الوصفية والبيانات الثنائية لخط يستخدم في مستند Presentation تم تحميله في كائن Viewer."
type: docs
weight: 15
url: /ar/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

يغلف البيانات الوصفية والبيانات الثنائية لخط يستخدم في مستند Presentation، تم تحميله في كائن Viewer. يُستخدم هذا الخط في محتوى المستند وقد يكون مدمجًا داخل المستند نفسه أو مثبتًا في نظام التشغيل حيث يعمل GroupDocs.Viewer.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | يحصل على اسم عائلة الخط (لا يكون أبداً null أو فارغ). |
|
|  | [getStyle()](#getStyle--) | يحصل على نمط الخط: Regular أو Bold أو Italic أو BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | يشير إلى ما إذا كان هذا الخط مدمجًا داخل المستند المحمَّل في كائن Viewer. |
|
|  | [getFormat()](#getFormat--) | يحصل على تنسيق الخط (TrueType، OpenType، إلخ). |
|
|  | [getContent()](#getContent--) | يحصل على المحتوى الثنائي للخط، أو null إذا كانت بيانات الخط غير متوفرة. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | يسلسل معلومات هذا الخط إلى قاعدة CSS @font-face باستخدام الكاتب المحدد. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل على اسم عائلة الخط (لا يكون أبداً null أو فارغ).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


يحصل على نمط الخط: Regular أو Bold أو Italic أو BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


يشير إلى ما إذا كان هذا الخط مدمجًا داخل المستند المحمَّل في كائن Viewer. ملاحظة: مستندات Spreadsheet لا يمكنها احتواء خطوط مدمجة، لذا بالنسبة لها دائمًا ما تعيد false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


يحصل على تنسيق الخط (TrueType، OpenType، إلخ). إذا كانت البيانات الوصفية فقط متاحة، يعيد FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


يحصل على المحتوى الثنائي للخط، أو null إذا كانت بيانات الخط غير متوفرة.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


يسلسل معلومات هذا الخط إلى قاعدة CSS @font-face باستخدام الكاتب المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | output | java.io.Writer | كاتب لكتابة CSS فيه (يجب ألا يكون null). |
|

