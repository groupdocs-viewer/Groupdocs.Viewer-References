---
title: "TimeUnit"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "وحدة الوقت لمدة المشروع."
type: docs
weight: 47
url: /ar/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

وحدة الوقت لمدة المشروع.

تُظهر تعداد TimeUnit وحدات زمنية مختلفة لتحديد مدة المشروع في مكوّن GroupDocs.Viewer. يوفر مجموعة من الوحدات الزمنية المعرفة مسبقًا التي يمكن استخدامها لتمثيل وحساب مدة المشروع، مثل الأيام والشهور وما إلى ذلك. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## الحقول

| حقل | الوصف |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | مقياس الوقت غير المعروف. |
| [DAYS](#DAYS) | مقياس الوقت بالأيام. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | مقياس الوقت بثلاثة أجزاء من الشهر. |
| [MONTHS](#MONTHS) | مقياس الوقت بالشهور. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


مقياس الوقت غير المعروف. تمثل وحدة الوقت هذه مقياسًا غير معروف أو غير محدد.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


مقياس الوقت بالأيام. تمثل وحدة الوقت هذه فاصلًا يوميًا واحدًا.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


مقياس الوقت بثلاثة أجزاء من الشهر. تمثل وحدة الوقت هذه فاصلًا يساوي ثلث الشهر.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


مقياس الوقت بالشهور. تمثل وحدة الوقت هذه فاصلًا شهريًا واحدًا.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

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
| الاسم | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
