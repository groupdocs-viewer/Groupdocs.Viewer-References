---
title: "FontStyles"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل 4 أنماط محتملة للخط المستخدم في المستند: Regular أو Bold أو Italic أو Bold Italic."
type: docs
weight: 13
url: /ar/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

يمثل 4 أنماط محتملة للخط، المستخدمة في المستند: عادي، غامق، مائل، أو غامق مائل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | ينشئ كائن FontStyles من علامات bold/italic. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [toString(int style)](#toString-int-) | يحوّل قيمة النمط إلى سلسلة قابلة للقراءة من قبل الإنسان. |
|
|  | [getName()](#getName--) | يرجع الاسم القابل للقراءة لهذا النمط من الخط. |
|
|  | [isBold()](#isBold--) | يعيد true إذا تم تعيين بت الغامق. |
|
|  | [isItalic()](#isItalic--) | يعيد true إذا تم تعيين بت المائل. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | الاتحاد (C# operator +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | الفرق (C# operator -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | يقوم بتحليل اسم نمط الخط إلى FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


ينشئ كائن FontStyles من علامات bold/italic.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


يحوّل قيمة النمط إلى سلسلة قابلة للقراءة من قبل الإنسان.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نمط | int | قيمة نمط الخط |
|

**Returns:**
java.lang.String - تمثيل نصي لنمط الخط

### getName() {#getName--}
```
public String getName()
```


يرجع الاسم القابل للقراءة لهذا النمط من الخط.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


يعيد true إذا تم تعيين بت الغامق.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


يعيد true إذا تم تعيين بت المائل.


**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


الاتحاد (C# operator +)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأول | com.groupdocs.viewer.fonts.FontStyles |  |
| الثاني | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


الفرق (C# operator -)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المُطرح منه | com.groupdocs.viewer.fonts.FontStyles |  |
| المُطرح | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


يقوم بتحليل اسم نمط الخط إلى FontStyles.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نمط | java.lang.String |  |
| تم التحليل | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true عند النجاح، false غير ذلك.

