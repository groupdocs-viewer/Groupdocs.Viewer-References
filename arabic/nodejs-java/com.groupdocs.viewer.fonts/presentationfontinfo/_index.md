---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحتوي على بيانات التعريف والبيانات الثنائية لخط يُستخدم في مستند عرض تقديمي محمَّل في كائن Viewer."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

يحتوي على بيانات التعريف والبيانات الثنائية لخط يُستخدم في مستند عرض تقديمي، محمَّل في كائن Viewer. يُستخدم هذا الخط في محتوى المستند وقد يكون مضمّنًا داخل المستند نفسه أو مُثبتًا في نظام التشغيل الذي يعمل عليه GroupDocs.Viewer.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | يحصل على اسم عائلة الخط (لا يكون أبداً فارغًا أو null). |
| [getStyle()](#getStyle--) | يحصل على نمط الخط: Regular أو Bold أو Italic أو BoldItalic. |
| [isEmbedded()](#isEmbedded--) | يشير إلى ما إذا كان هذا الخط مضمّنًا داخل المستند المحمَّل في كائن Viewer. |
| [getFormat()](#getFormat--) | يحصل على تنسيق الخط (TrueType، OpenType، إلخ). |
| [getContent()](#getContent--) | يحصل على محتوى الخط الثنائي، أو null إذا كانت بيانات الخط غير متوفرة. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | يسلسل معلومات هذا الخط إلى قاعدة CSS @font-face باستخدام الكاتب المحدد. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يحصل على اسم عائلة الخط (لا يكون أبداً فارغًا أو null).

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


يشير إلى ما إذا كان هذا الخط مضمّنًا داخل المستند المحمَّل في كائن Viewer. ملاحظة: لا يمكن لمستندات الجداول الإلكترونية احتواء خطوط مضمّنة، لذا فإنها دائمًا تُرجع false.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


يحصل على تنسيق الخط (TrueType، OpenType، إلخ). إذا كانت البيانات التعريفية فقط متاحة، يُرجع FontFormat.Unknown.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


يحصل على محتوى الخط الثنائي، أو null إذا كانت بيانات الخط غير متوفرة.

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
| الإخراج | java.io.Writer | كاتب لكتابة CSS فيه (يجب ألا يكون فارغًا) |

