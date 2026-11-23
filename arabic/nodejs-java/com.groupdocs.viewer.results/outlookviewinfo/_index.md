---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل معلومات العرض لملف بيانات Outlook."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

يمثل معلومات العرض لملف بيانات Outlook.

تحدد واجهة OutlookViewInfo العقد للوصول إلى معلومات العرض ومعالجتها لملف بيانات Outlook في مكوّن GroupDocs.Viewer. توفر طرقًا لاسترجاع معلومات مثل قائمة المجلدات وغيرها من الخصائص.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFolders()](#getFolders--) | يسترجع قائمة المجلدات الموجودة في ملف بيانات Outlook. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | يضبط قائمة المجلدات الموجودة في ملف بيانات Outlook. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


يسترجع قائمة المجلدات الموجودة في ملف بيانات Outlook.

**Returns:**
java.util.List<java.lang.String> - قائمة المجلدات.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


يضبط قائمة المجلدات الموجودة في ملف بيانات Outlook.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قائمة | java.util.List<java.lang.String> | قائمة المجلدات. |

