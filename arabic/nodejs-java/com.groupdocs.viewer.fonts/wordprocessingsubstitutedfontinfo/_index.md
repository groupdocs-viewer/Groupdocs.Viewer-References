---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يغلف البيانات الوصفية والبيانات الثنائية لخط مستبدل واحد مستخدم في مستند WordProcessing عبر GroupDocs.Viewer."
type: docs
weight: 18
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

يغلف البيانات الوصفية والبيانات الثنائية لخط مستبدل واحد يُستخدم في مستند WordProcessing عبر GroupDocs.Viewer. فئة غير قابلة للتغيير.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | منشئ لتهيئة جميع الحقول. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | يرجع اسم العائلة للخط المستبدل (دائمًا غير null). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | يرجع اسم العائلة للخط الأصلي (دائمًا غير null). |
| [getStyle()](#getStyle--) | يرجع نمط الخط الأصلي. |
| [getContent()](#getContent--) | يرجع المحتوى الثنائي للخط المستبدل (دائمًا غير null). |
| [getFormat()](#getFormat--) | يرجع تنسيق الخط للخط المستبدل. |
| [toString()](#toString--) | يرجع سلسلة تصف هذا الخط المستبدل: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | المساواة تعتمد على عائلة الخط الأصلي، عائلة الخط المستبدل، والنمط. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | تسلسل هذا الخط كقاعدة CSS @font-face باستخدام طريقة مساعدة. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


منشئ لتهيئة جميع الحقول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| originalFamilyName | java.lang.String | اسم الخط الأصلي (غير موجود في النظام) |
| substitutedFamilyName | java.lang.String | اسم الخط المستبدل (متوفر) |
| النمط | com.groupdocs.viewer.fonts.FontStyles | نمط الخط (Regular, Bold, Italic, BoldItalic) |
| content | byte[] | المحتوى الثنائي للخط المستبدل (دائمًا غير null) |
| format | int | تنسيق الخط (TrueType, OpenType, إلخ) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يرجع اسم العائلة للخط المستبدل (دائمًا غير null).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


يرجع اسم العائلة للخط الأصلي (دائمًا غير null).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


يرجع نمط الخط الأصلي.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


يرجع المحتوى الثنائي للخط المستبدل (دائمًا غير null).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


يرجع تنسيق الخط للخط المستبدل.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تصف هذا الخط المستبدل: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


المساواة تعتمد على عائلة الخط الأصلي، عائلة الخط المستبدل، والنمط. مطلوب للاستخدام في HashSet أو HashMap مثل C\# IEqualityComparer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


تسلسل هذا الخط كقاعدة CSS @font-face باستخدام طريقة مساعدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإخراج | java.io.Writer |  |

