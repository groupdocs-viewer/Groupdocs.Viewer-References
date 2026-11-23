---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على معلومات تعريفية وبيانات ثنائية لخط واحد من مستند WordProcessing المحمَّل في نسخة Viewer."
type: docs
weight: 17
url: /ar/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

يحتوي على معلومات تعريفية وبيانات ثنائية لخط واحد من مستند WordProcessing، المحمَّل في نسخة Viewer. يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer.

فئة غير قابلة للتغيير. تُنتج مثيلاتها وتُرجعها GroupDocs.Viewer
واجهة برمجة تطبيقات عامة وعادةً لا ينبغي إنشاؤها من قبل المستخدم.
للتفاصيل، راجع الوثائق:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | اسم عائلة الخط، بدون النمط، لا يكون أبداً null أو فارغ. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | اسم عائلة بديل للخط. |
|
|  | [getStyle()](#getStyle--) | نمط الخط — قد يكون Regular أو Bold أو Italic أو BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | يشير إلى ما إذا كان هذا الخط مدمجًا داخل المستند (true) أو خط نظام (false). |
|
|  | [getFormat()](#getFormat--) | تنسيق هذا الخط. |
|
|  | [getContent()](#getContent--) | محتوى هذا الخط كمصفوفة بايت، أو null إذا كان غير متوفر. |
|
|  | [getCharset()](#getCharset--) | مجموعة الأحرف لهذا الخط. |
|
|  | [toString()](#toString--) | يعيد معلومات تصحيح الأخطاء حول هذا الخط وفق القالب التالي: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | يسلسل معلومات هذا الخط كقاعدة CSS @font-face ويكتبها إلى الكاتب المحدد. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


اسم عائلة الخط، بدون النمط، لا يكون أبداً null أو فارغ.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


اسم عائلة بديل للخط. إذا كان مفقودًا، يعيد سلسلة فارغة.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


نمط الخط — قد يكون Regular أو Bold أو Italic أو BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


يشير إلى ما إذا كان هذا الخط مدمجًا داخل المستند (true) أو خط نظام (false).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


تنسيق هذا الخط. إذا كان هناك فقط بيانات تعريفية ومحتوى بايت مفقود، قد يعيد FontFormat.UNKNOWN.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


محتوى هذا الخط كمصفوفة بايت، أو null إذا كان غير متوفر.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


مجموعة الأحرف لهذا الخط.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


يعيد معلومات تصحيح الأخطاء حول هذا الخط وفق القالب التالي: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


يسلسل معلومات هذا الخط كقاعدة CSS @font-face ويكتبها إلى الكاتب المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | output | java.io.Writer | كاتب لاستلام CSS المتسلسل. |
|

