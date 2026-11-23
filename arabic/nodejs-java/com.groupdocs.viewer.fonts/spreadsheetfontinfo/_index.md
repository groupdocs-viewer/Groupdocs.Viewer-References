---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يغلف البيانات الوصفية والبيانات الثنائية لخط واحد من مستند Spreadsheet المحمَّل في كائن Viewer."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

يغلف البيانات الوصفية والبيانات الثنائية لخط واحد من مستند Spreadsheet، المحمَّل في كائن Viewer. لا يمكن لمستندات Spreadsheet أن تحتوي على خطوط مدمجة، لذا فإن هذا الخط المحدد، إذا تم إرجاعه بواسطة طريقة Viewer.getAllFonts()، يتم تثبيته في نظام التشغيل الذي يعمل عليه GroupDocs.Viewer.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو null. |
| [getStyle()](#getStyle--) | نمط هذا الخط \u2014 قد يكون Regular أو Bold أو Italic أو BoldItalic. |
| [isStrikeout()](#isStrikeout--) | يشير إلى ما إذا كان الخط يحتوي على خط وسط واحد. |
| [isUnderline()](#isUnderline--) | يشير إلى ما إذا كان الخط يحتوي على خط سفلي. |
| [getColor()](#getColor--) | لون هذا الخط. |
| [getCharset()](#getCharset--) | مجموعة الأحرف لهذا الخط. |
| [getContent()](#getContent--) | محتوى هذا الخط كمصفوفة بايت. |
| [getFormat()](#getFormat--) | تنسيق هذا الخط. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى الكاتب المحدد. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو null.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


نمط هذا الخط \u2014 قد يكون Regular أو Bold أو Italic أو BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


يشير إلى ما إذا كان الخط يحتوي على خط وسط واحد.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


يشير إلى ما إذا كان الخط يحتوي على خط سفلي.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


لون هذا الخط.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


مجموعة الأحرف لهذا الخط.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


محتوى هذا الخط كمصفوفة بايت. قد يكون فارغًا إذا كانت المعلومات الوصفية فقط متاحة.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


تنسيق هذا الخط.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى الكاتب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإخراج | java.io.Writer | الجهاز لكتابة البيانات النصية المتسلسلة فيه. |

