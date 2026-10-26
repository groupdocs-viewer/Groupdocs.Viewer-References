---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل معلومات العرض لملف أرشيف."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

يمثل معلومات العرض لملف أرشيف.

تحدد واجهة ArchiveViewInfo العقد لاسترجاع معلومات العرض الخاصة بملف الأرشيف في مكوّن GroupDocs.Viewer. توفر طرقًا للوصول إلى تفاصيل مثل عدد الصفحات، الأبعاد، وخيارات العرض الخاصة بملفات الأرشيف.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFolders()](#getFolders--) | يسترجع قائمة المجلدات الموجودة داخل ملف الأرشيف. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | يضبط قائمة المجلدات الموجودة داخل ملف الأرشيف. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


يسترجع قائمة المجلدات الموجودة داخل ملف الأرشيف.

**Returns:**
java.util.List<java.lang.String> - قائمة المجلدات.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


يضبط قائمة المجلدات الموجودة داخل ملف الأرشيف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المجلدات | java.util.List<java.lang.String> | قائمة المجلدات. |

