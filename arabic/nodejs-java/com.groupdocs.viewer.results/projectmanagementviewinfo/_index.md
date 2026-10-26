---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل معلومات العرض لمستند MS Project."
type: docs
weight: 23
url: /ar/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

يمثل معلومات العرض لمستند MS Project.

تحدد واجهة ProjectManagementViewInfo العقد للوصول إلى معلومات العرض وتعديلها لمستند MS Project في مكوّن GroupDocs.Viewer. وتوفر طرقًا لاسترجاع معلومات مثل تاريخ البدء وتاريخ الانتهاء، وغيرها من الخصائص.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getStartDate()](#getStartDate--) | يسترجع التاريخ والوقت الذي بدأ فيه المشروع. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | يضبط تاريخ ووقت بدء المشروع. |
| [getEndDate()](#getEndDate--) | يسترجع التاريخ والوقت الذي سيكتمل فيه المشروع. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | يضبط تاريخ ووقت انتهاء المشروع. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


يسترجع التاريخ والوقت الذي بدأ فيه المشروع.

**Returns:**
java.util.Date - تاريخ ووقت بدء المشروع.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


يضبط تاريخ ووقت بدء المشروع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startDate | java.util.Date | تاريخ ووقت البدء الجديد الذي سيتم ضبطه. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


يسترجع التاريخ والوقت الذي سيكتمل فيه المشروع.

**Returns:**
java.util.Date - تاريخ ووقت انتهاء المشروع.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


يضبط تاريخ ووقت انتهاء المشروع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| endDate | java.util.Date | تاريخ ووقت الانتهاء الجديد الذي سيتم ضبطه. |

