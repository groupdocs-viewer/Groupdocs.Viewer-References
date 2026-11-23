---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "Provides options for rendering project management files."
type: docs
weight: 27
url: /ar/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Provides options for rendering project management files.

فئة ProjectManagementOptions تضم إعدادات ومعلمات مختلفة يمكن استخدامها للتحكم في عرض ملفات إدارة المشاريع (مثل Microsoft Project أو ما شابه) في مكوّن GroupDocs.Viewer. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | يُنشئ مثلاً جديداً من الفئة ProjectManagementOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageSize()](#getPageSize--) | يسترجع حجم صفحة الإخراج. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | يحدد حجم صفحة الإخراج. |
| [getTimeUnit()](#getTimeUnit--) | يسترجع وحدة الوقت. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | يسترجع وحدة الوقت. |
| [getStartDate()](#getStartDate--) | يسترجع تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الإخراج. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | يحدد تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الإخراج. |
| [getEndDate()](#getEndDate--) | يسترجع تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الإخراج. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | يحدد تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الإخراج. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


يُنشئ مثلاً جديداً من الفئة ProjectManagementOptions.

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


يسترجع حجم صفحة الإخراج.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


يحدد حجم صفحة الإخراج.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | حجم صفحة الإخراج. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


يسترجع وحدة الوقت.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


يسترجع وحدة الوقت.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | وحدة الوقت. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


يسترجع تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الإخراج.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - تاريخ البدء لعرض مخطط جانت.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


يحدد تاريخ البدء لعرض مخطط جانت الذي سيُضمّن في الإخراج.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.Date | تاريخ البدء لعرض مخطط جانت. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


يسترجع تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الإخراج.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - تاريخ الانتهاء لعرض مخطط جانت.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


يحدد تاريخ الانتهاء لعرض مخطط جانت الذي سيُضمّن في الإخراج.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.Date | تاريخ الانتهاء لعرض مخطط جانت. |

