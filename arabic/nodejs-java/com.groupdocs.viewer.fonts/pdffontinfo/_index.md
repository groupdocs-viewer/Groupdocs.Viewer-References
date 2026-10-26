---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحتوي على معلومات وصفية وبيانات ثنائية لخط واحد من مستند PDF محمَّل في مثيل Viewer."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

يغلف المعلومات الوصفية والبيانات الثنائية لخط واحد من مستند PDF، تم تحميله في نسخة Viewer.

يُستخدم هذا الخط في محتوى المستند وهو إما:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | منشئ داخلي يُستخدم لاستخراج خطوط PDF. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | يحصل على اسم عائلة الخط. |
| [getStyle()](#getStyle--) | يحصل على نمط هذا الخط. |
| [isEmbedded()](#isEmbedded--) | يرجع ما إذا كان الخط مضمنًا داخل مستند PDF. |
| [isInstalled()](#isInstalled--) | يرجع ما إذا كان الخط مثبتًا في نظام التشغيل. |
| [getFormat()](#getFormat--) | يرجع تنسيق ملف الخط. |
| [getContent()](#getContent--) | يرجع المحتوى الثنائي للخط. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | يسلسل هذا الخط كقاعدة CSS  @font-face  . |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


منشئ داخلي يُستخدم لاستخراج خطوط PDF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| familyName | java.lang.String | اسم عائلة الخط |
| النمط | com.groupdocs.viewer.fonts.FontStyles | النمط (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true إذا كان الخط مضمنًا في PDF |
| isInstalled | boolean | true إذا كان الخط مثبتًا في نظام التشغيل |
| content | byte[] | بيانات الخط الثنائية (قابلة للفراغ) |
| format | int | تنسيق ملف الخط |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل على اسم عائلة الخط.

**Returns:**
java.lang.String - سلسلة اسم العائلة (أبدًا لا تكون null أو فارغة)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


يحصل على نمط هذا الخط.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - نمط الخط
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


يرجع ما إذا كان الخط مضمنًا داخل مستند PDF.

**Returns:**
boolean - true إذا كان مضمنًا
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


يرجع ما إذا كان الخط مثبتًا في نظام التشغيل.

**Returns:**
boolean - true إذا كان مثبتًا
### getFormat() {#getFormat--}
```
public int getFormat()
```


يرجع تنسيق ملف الخط.

**Returns:**
int - تعداد تنسيق الخط
### getContent() {#getContent--}
```
public byte[] getContent()
```


يرجع المحتوى الثنائي للخط.

**Returns:**
byte[] - مصفوفة بايت أو null إذا غير متوفر
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


يسلسل هذا الخط كقاعدة CSS  @font-face  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإخراج | java.io.Writer | writer الذي سيُكتب إليه CSS |

