---
title: "TimeUnit"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "وحدة الوقت لمدة المشروع."
type: docs
weight: 47
url: /ar/java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

وحدة الوقت لمدة المشروع.


عدد TimeUnit يمثل وحدات زمنية مختلفة لتحديد مدة مشروع في مكوّن GroupDocs.Viewer.
يوفر مجموعة من الوحدات الزمنية المعرفة مسبقًا يمكن استخدامها لتمثيل وحساب مدة المشروع،
مثل الأيام، الشهور وهكذا.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


مثال على الاستخدام:

````

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | مقياس الوقت غير المعروف. |
|
|  | [DAYS](#DAYS) | مقياس الوقت بالأيام. |
|
|  | [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | مقياس زمني لثلث الشهر. |
|
|  | [MONTHS](#MONTHS) | مقياس زمني للشهر. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


مقياس الوقت غير المعروف.
تمثل وحدة الوقت هذه مقياسًا زمنيًا غير معروف أو غير محدد.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


مقياس الوقت بالأيام.
تمثل وحدة الوقت هذه فاصلًا يوميًا واحدًا.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


مقياس زمني لثلث الشهر.
تمثل وحدة الوقت هذه فاصلًا يساوي ثلث الشهر.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


مقياس زمني للشهر.
تمثل وحدة الوقت هذه فاصلًا شهريًا واحدًا.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
