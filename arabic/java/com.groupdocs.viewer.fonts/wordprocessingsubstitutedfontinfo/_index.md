---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يغلف البيانات الوصفية والبيانات الثنائية لخط مستبدل واحد يُستخدم في مستند WordProcessing عبر GroupDocs.Viewer."
type: docs
weight: 18
url: /ar/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد مستبدل يُستخدم في مستند WordProcessing عبر GroupDocs.Viewer. فئة غير قابلة للتغيير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | منشئ لتهيئة جميع الحقول. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | يعيد اسم العائلة للخط المستبدل (أبدًا لا يكون فارغًا). |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | يعيد اسم العائلة للخط الأصلي (أبدًا لا يكون فارغًا). |
|
|  | [getStyle()](#getStyle--) | يعيد نمط الخط الأصلي. |
|
|  | [getContent()](#getContent--) | يعيد المحتوى الثنائي للخط المستبدل (أبدًا لا يكون فارغًا). |
|
|  | [getFormat()](#getFormat--) | يعيد تنسيق الخط للخط المستبدل. |
|
|  | [toString()](#toString--) | يعيد سلسلة تصف هذا الخط المستبدل: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | المساواة تعتمد على العائلة الأصلية، العائلة المستبدلة، والنمط. |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | تحويل هذا الخط إلى قاعدة CSS @font-face باستخدام طريقة مساعدة. |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


منشئ لتهيئة جميع الحقول.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | اسم الخط الأصلي (غير موجود في النظام) |
|
|  | substitutedFamilyName | java.lang.String | اسم الخط المستبدل (متاح) |
|
|  | نمط | com.groupdocs.viewer.fonts.FontStyles | نمط الخط (Regular, Bold, Italic, BoldItalic) |
|
|  | content | byte[] | المحتوى الثنائي للخط المستبدل (أبدًا لا يكون فارغًا) |
|
|  | التنسيق | int | تنسيق الخط (TrueType, OpenType, إلخ) |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


يعيد اسم العائلة للخط المستبدل (أبدًا لا يكون فارغًا).


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


يعيد اسم العائلة للخط الأصلي (أبدًا لا يكون فارغًا).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


يعيد نمط الخط الأصلي.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


يعيد المحتوى الثنائي للخط المستبدل (أبدًا لا يكون فارغًا).


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


يعيد تنسيق الخط للخط المستبدل.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تصف هذا الخط المستبدل: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


المساواة تعتمد على العائلة الأصلية، العائلة المستبدلة، والنمط. مطلوب للاستخدام في HashSet أو HashMap مثل C# IEqualityComparer.


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


تحويل هذا الخط إلى قاعدة CSS @font-face باستخدام طريقة مساعدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| output | java.io.Writer |  |

