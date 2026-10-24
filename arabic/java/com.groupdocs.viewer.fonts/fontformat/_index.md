---
title: "FontFormat"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل جميع صيغ الخط التي قد تكون موجودة في فئة UsedFontInfo."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

يمثل جميع صيغ الخطوط التي قد تكون موجودة في الفئة UsedFontInfo.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Unknown](#Unknown) | صيغة خط غير معروفة أو غير صالحة. |
|
|  | [TrueType](#TrueType) | صيغة خط TrueType (TTF). |
|
|  | [OpenType](#OpenType) | صيغة خط OpenType (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | صيغة مجموعة خطوط TrueType (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | صيغة خط OpenType المدمج (EOT). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [toString(int format)](#toString-int-) | يحوّل قيمة الصيغة إلى سلسلة قابلة للقراءة من قبل الإنسان. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


صيغة خط غير معروفة أو غير صالحة.


### TrueType {#TrueType}
```
public static final int TrueType
```


صيغة خط TrueType (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


صيغة خط OpenType (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


صيغة مجموعة خطوط TrueType (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


صيغة خط OpenType المدمج (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


يحوّل قيمة الصيغة إلى سلسلة قابلة للقراءة من قبل الإنسان.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التنسيق | int | قيمة صيغة الخط |
|

**Returns:**
java.lang.String - تمثيل نصي لصيغة الخط

