---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل معلومات العرض لمستند MS Project."
type: docs
weight: 25
url: /ar/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

يمثل معلومات العرض لمستند MS Project.


تحدد واجهة ProjectManagementViewInfo العقد للوصول إلى معلومات العرض ومعالجتها
لمستند MS Project في مكوّن GroupDocs.Viewer. يوفر طرقًا لاسترجاع المعلومات
مثل تواريخ البداية والنهاية، وغيرها من الخصائص.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | يسترجع التاريخ والوقت الذي بدأ منه المشروع. |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | يضبط تاريخ ووقت البداية للمشروع. |
|
|  | [getEndDate()](#getEndDate--) | يسترجع التاريخ والوقت الذي من المقرر إكمال المشروع فيه. |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | يضبط تاريخ ووقت النهاية للمشروع. |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


يسترجع التاريخ والوقت الذي بدأ منه المشروع.


**Returns:**
java.util.Date - تاريخ ووقت البداية للمشروع.

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


يضبط تاريخ ووقت البداية للمشروع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startDate | java.util.Date | تاريخ ووقت البداية الجديد الذي سيتم ضبطه. |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


يسترجع التاريخ والوقت الذي من المقرر إكمال المشروع فيه.


**Returns:**
java.util.Date - تاريخ ووقت النهاية للمشروع.

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


يضبط تاريخ ووقت النهاية للمشروع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | endDate | java.util.Date | تاريخ ووقت النهاية الجديد الذي سيتم ضبطه. |
|

