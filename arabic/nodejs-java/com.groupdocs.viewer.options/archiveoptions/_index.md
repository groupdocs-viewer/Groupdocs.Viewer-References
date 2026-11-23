---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض ملفات الأرشيف."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

يوفر خيارات لعرض ملفات الأرشيف.

الفئة  ArchiveOptions  تمثل مجموعة من الخيارات التي يمكن استخدامها لتكوين عرض ملفات الأرشيف في وحدة العارض. تتيح لك تخصيص جوانب مختلفة من عملية العرض، مثل عدد العناصر في كل صفحة وما إلى ذلك.

مثال على الاستخدام:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | ينشئ نسخة جديدة من الفئة ArchiveOptions بإعدادات افتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFolder()](#getFolder--) | يحصل على المجلد داخل الأرشيف الذي سيُستخدم للعرض. |
| [setFolder(String value)](#setFolder-java.lang.String-) | يضبط المجلد داخل الأرشيف الذي سيُستخدم في العرض. |
| [getFileName()](#getFileName--) | يحصل على اسم الملف الذي سيُعرض في الترويسة. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | يضبط اسم الملف الذي سيُعرض في الترويسة. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


ينشئ نسخة جديدة من الفئة ArchiveOptions بإعدادات افتراضية.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


يحصل على المجلد داخل الأرشيف الذي سيُستخدم للعرض.

بشكل افتراضي، يقوم GroupDocs.Viewer بعرض العناصر من جميع المجلدات الموجودة في الأرشيف. لعرض العناصر من مجلد محدد، اضبط هذه الخاصية. للحصول على مثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - المجلد الذي سيتم عرضه.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


يضبط المجلد داخل الأرشيف الذي سيُستخدم في العرض.

بشكل افتراضي، يقوم GroupDocs.Viewer بعرض العناصر من جميع المجلدات الموجودة في الأرشيف. لعرض العناصر من مجلد محدد، اضبط هذه الخاصية. للحصول على مثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | المجلد الذي سيتم عرضه. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


يحصل على اسم الملف الذي سيُعرض في الترويسة.

بشكل افتراضي، يعرض GroupDocs.Viewer اسم ملف الأرشيف في ترويسة كل صفحة. لتغيير هذا الاسم أو إخفائه، اضبط هذه الخاصية. لمزيد من المعلومات ومثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


يضبط اسم الملف الذي سيُعرض في الترويسة.

بشكل افتراضي، يعرض GroupDocs.Viewer اسم ملف الأرشيف في ترويسة كل صفحة. لتغيير هذا الاسم أو إخفائه، اضبط هذه الخاصية. لمزيد من المعلومات ومثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | اسم الملف الذي سيُعرض. |

