---
title: "PageSize"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "حجم الصفحة."
type: docs
weight: 42
url: /ar/java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

حجم الصفحة.


يمثل تعداد PageSize أحجام صفحات مختلفة في مكوّن GroupDocs.Viewer.
يوفر مجموعة من أحجام الصفحات المعرفة مسبقًا التي يمكن استخدامها لتحديد الأبعاد
لصفحة في سيناريوهات عرض المستندات المختلفة.


مثال على الاستخدام:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UNSPECIFIED](#UNSPECIFIED) | حجم الصفحة الافتراضي غير المحدد. |
|
|  | [LETTER](#LETTER) | حجم صفحة Letter بالنقاط هو 792 × 612. |
|
|  | [LEDGER](#LEDGER) | حجم صفحة A0 بالنقاط هو 3371 × 2384. |
|
|  | [A0](#A0) | حجم صفحة A1 بالنقاط هو 2384 × 1685. |
|
|  | [A1](#A1) | حجم صفحة A2 بالنقاط هو 1684 × 1190. |
|
|  | [A2](#A2) | حجم صفحة A3 بالنقاط هو 1190 × 842. |
|
|  | [A3](#A3) | حجم صفحة A3 بالنقاط هو 1190 × 842. |
|
|  | [A4](#A4) | حجم صفحة A4 بالنقاط هو 842 × 595. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


حجم الصفحة الافتراضي غير المحدد.
يُستخدم هذا الحجم عندما لا يتم تحديد حجم صفحة محدد.


### LETTER {#LETTER}
```
public static final PageSize LETTER
```


حجم صفحة Letter بالنقاط هو 792 × 612.
يُستخدم حجم الصفحة هذا عادةً للرسائل والوثائق في أمريكا الشمالية.


### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


حجم صفحة A0 بالنقاط هو 3371 × 2384.
هذا الحجم الكبير للصفحة هو جزء من المعيار الدولي ISO 216.


### A0 {#A0}
```
public static final PageSize A0
```


حجم صفحة A1 بالنقاط هو 2384 × 1685.
هذا الحجم للصفحة هو جزء من المعيار الدولي ISO 216.


### A1 {#A1}
```
public static final PageSize A1
```


حجم صفحة A2 بالنقاط هو 1684 × 1190.
هذا الحجم للصفحة هو جزء من المعيار الدولي ISO 216.


### A2 {#A2}
```
public static final PageSize A2
```


حجم صفحة A3 بالنقاط هو 1190 × 842.
هذا الحجم للصفحة هو جزء من المعيار الدولي ISO 216.


### A3 {#A3}
```
public static final PageSize A3
```


حجم صفحة A3 بالنقاط هو 1190 × 842.
هذا الحجم للصفحة هو جزء من المعيار الدولي ISO 216.


### A4 {#A4}
```
public static final PageSize A4
```


حجم صفحة A4 بالنقاط هو 842 × 595.
هذا الحجم للصفحة هو جزء من المعيار الدولي ISO 216.


### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
