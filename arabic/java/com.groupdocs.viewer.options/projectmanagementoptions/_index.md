---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير ملفات إدارة المشاريع."
type: docs
weight: 27
url: /ar/java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

يوفر خيارات لتصيير ملفات إدارة المشاريع.


تُجَمِّع فئة ProjectManagementOptions إعدادات ومعلمات مختلفة يمكن استخدامها
للتحكم في عرض ملفات إدارة المشاريع (مثل Microsoft Project أو ما شابه)
في مكوّن GroupDocs.Viewer.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


مثال على الاستخدام:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ProjectManagementOptions()](#ProjectManagementOptions--) | ينشئ مثلاً جديداً من |
ProjectManagementOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | يسترجع حجم الصفحة الناتج. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | يضبط حجم الصفحة الناتج. |
|
|  | [getTimeUnit()](#getTimeUnit--) | يسترجع وحدة الوقت. |
|
|  | [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | يسترجع وحدة الوقت. |
|
|  | [getStartDate()](#getStartDate--) | يسترجع تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الناتج. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | يضبط تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الناتج. |
|
|  | [getEndDate()](#getEndDate--) | يسترجع تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الناتج. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | يضبط تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الناتج. |
|
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


ينشئ مثلاً جديداً من
ProjectManagementOptions
الفئة.


### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


يسترجع حجم الصفحة الناتج.


لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


يضبط حجم الصفحة الناتج.


لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | حجم الصفحة الناتج. |
|

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


يسترجع وحدة الوقت.


لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.

### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


يسترجع وحدة الوقت.


لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | وحدة الوقت. |
|

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


يسترجع تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الناتج.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - تاريخ البدء لعرض مخطط جانت.

### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


يضبط تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الناتج.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.Date | تاريخ البدء لعرض مخطط جانت. |
|

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


يسترجع تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الناتج.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Returns:**
java.util.Date - تاريخ الانتهاء لعرض مخطط جانت.

### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


يضبط تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الناتج.


***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.*
لعينة الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.Date | تاريخ الانتهاء لعرض مخطط جانت. |
|

