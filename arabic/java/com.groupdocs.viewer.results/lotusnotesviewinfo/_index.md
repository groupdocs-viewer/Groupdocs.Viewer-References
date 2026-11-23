---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل معلومات العرض لتخزين قاعدة بيانات Lotus Notes."
type: docs
weight: 19
url: /ar/java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

يمثل معلومات العرض لتخزين قاعدة بيانات Lotus Notes.


واجهة LotusNotesViewInfo تحدد العقد للوصول إلى معلومات العرض ومعالجتها.
لتخزين قاعدة بيانات Lotus Notes في مكوّن GroupDocs.Viewer. توفر طرقًا لاسترجاع المعلومات.
مثل عدد الملاحظات، وغيرها من الخصائص.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getNotesCount()](#getNotesCount--) | يسترجع عدد الملاحظات في التخزين. |
|
|  | [setNotesCount(int count)](#setNotesCount-int-) | يضبط عدد الملاحظات في التخزين. |
|
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


يسترجع عدد الملاحظات في التخزين.


**Returns:**
int - عدد الملاحظات في التخزين.

### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


يضبط عدد الملاحظات في التخزين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | العدد | int | عدد الملاحظات في التخزين. |
|

