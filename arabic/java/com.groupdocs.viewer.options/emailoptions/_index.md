---
title: "EmailOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لعرض رسائل البريد الإلكتروني."
type: docs
weight: 14
url: /ar/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

يوفر خيارات لعرض رسائل البريد الإلكتروني.


فئة EmailOptions تُجَمِّع إعدادات ومعلمات مختلفة يمكن استخدامها
للتحكم في عرض رسائل البريد الإلكتروني في مكوّن GroupDocs.Viewer.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


مثال على الاستخدام:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | ينشئ مثلاً جديداً من |
EmailOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | يحصل على تنسيق الوقت لتواريخ القيم والوقت. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | يحصل على تنسيق الوقت لتواريخ القيم والوقت. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | يحصل على إزاحة المنطقة الزمنية للرسالة. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | يحصل على إزاحة دقائق المنطقة الزمنية للرسالة. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | يحصل على إزاحة المنطقة الزمنية للرسالة. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | يحصل على إزاحة دقائق المنطقة الزمنية للرسالة. |
|
|  | [getPageSize()](#getPageSize--) | يحصل على حجم الصفحة الناتجة. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | يحصل على حجم الصفحة الناتجة. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | يسترجع التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | يضبط التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | يتجاوز طريقة equals() في فئة Object. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | يتجاوز طريقة toString() في فئة Object. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


ينشئ مثلاً جديداً من
EmailOptions
الفئة.
يُستخدم هذا المنشئ لإنشاء نسخة جديدة من
EmailOptions
الفئة مع الإعدادات الافتراضية.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


يحصل على تنسيق الوقت لتواريخ القيم والوقت.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
إذا لم يتم تعيين تنسيق الوقت، سيتم استخدام تنسيق النظام الحالي.
للتفاصيل، راجع الـ [الوثائق](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - تنسيق الوقت لقيم التاريخ والوقت.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


يحصل على تنسيق الوقت لتواريخ القيم والوقت.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
إذا لم يتم تعيين تنسيق الوقت، سيتم استخدام تنسيق النظام الحالي.
للتفاصيل، راجع الـ [الوثائق](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | تنسيق الوقت لقيم التاريخ والوقت. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


يحصل على إزاحة المنطقة الزمنية للرسالة.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
للتفاصيل، راجع الـ [الوثائق](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - إزاحة المنطقة الزمنية.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


يحصل على إزاحة دقائق المنطقة الزمنية للرسالة.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
للتفاصيل، راجع الـ [الوثائق](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - إزاحة المنطقة الزمنية.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


يحصل على إزاحة المنطقة الزمنية للرسالة.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | إزاحة المنطقة الزمنية. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


يحصل على إزاحة دقائق المنطقة الزمنية للرسالة.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | offsetMinutes | int | إزاحة المنطقة الزمنية. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


يحصل على حجم الصفحة الناتجة.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


يحصل على حجم الصفحة الناتجة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | حجم الصفحة. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


يسترجع التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


يضبط التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | التخطيط بين حقول رسالة البريد الإلكتروني وتمثيلاتها النصية. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


يتجاوز طريقة equals() في فئة Object.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | o | java.lang.Object | الكائن للمقارنة معه. |
|

**Returns:**
boolean - true إذا كانت الكائنات متساوية، false خلاف ذلك.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسب قيمة رمز التجزئة لهذا الكائن. رمز التجزئة يعتمد على
الحالة الداخلية للكائن ويستخدم في هياكل البيانات القائمة على التجزئة
مثل خرائط التجزئة ومجموعات التجزئة.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
عدد صحيح - قيمة رمز التجزئة لهذا الكائن.

### toString() {#toString--}
```
public String toString()
```


يتجاوز طريقة toString() في فئة Object.


**Returns:**
java.lang.String - تمثيل نصي للكائن.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


يرجع تمثيلاً نصيًا لهذا الكائن.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نمط | org.apache.commons.lang3.builder.ToStringStyle | نمط ToStringStyle المستخدم لإنشاء التمثيل النصي. |
|

**Returns:**
java.lang.String - تمثيل نصي لهذا الكائن باستخدام ToStringStyle المحدد.

