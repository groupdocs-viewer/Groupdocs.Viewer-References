---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لعرض ملفات الأرشيف."
type: docs
weight: 10
url: /ar/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

يوفر خيارات لعرض ملفات الأرشيف.


ال
ArchiveOptions
الفئة تمثل مجموعة من الخيارات التي يمكن استخدامها لتكوين عرض ملفات الأرشيف في وحدة المشاهد.
تتيح لك تخصيص جوانب مختلفة من عملية العرض، مثل عدد العناصر في كل صفحة وما إلى ذلك.


مثال على الاستخدام:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
الفئة توفر مجموعة من خيارات التخصيص لعرض ملفات الأرشيف.
يمكنك تكوين هذه الخيارات بناءً على متطلباتك الخاصة لتحقيق النتيجة المطلوبة.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | ينشئ مثيلاً جديداً من فئة ArchiveOptions بالإعدادات الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFolder()](#getFolder--) | يحصل على المجلد داخل الأرشيف الذي سيُستخدم للعرض. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | يضبط المجلد داخل الأرشيف الذي سيُستخدم للعرض. |
|
|  | [getFileName()](#getFileName--) | يحصل على اسم الملف الذي سيُعرض في الرأس. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | يضبط اسم الملف الذي سيُعرض في الرأس. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


ينشئ مثيلاً جديداً من فئة ArchiveOptions بالإعدادات الافتراضية.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


يحصل على المجلد داخل الأرشيف الذي سيُستخدم للعرض.


بشكل افتراضي، يقوم GroupDocs.Viewer بعرض العناصر من جميع المجلدات الموجودة في الأرشيف. لعرض العناصر من مجلد محدد، اضبط هذه الخاصية.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder).


**Returns:**
java.lang.String - المجلد الذي سيتم عرضه.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


يضبط المجلد داخل الأرشيف الذي سيُستخدم للعرض.


بشكل افتراضي، يقوم GroupDocs.Viewer بعرض العناصر من جميع المجلدات الموجودة في الأرشيف. لعرض العناصر من مجلد محدد، اضبط هذه الخاصية.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | المجلد الذي سيتم عرضه. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


يحصل على اسم الملف الذي سيُعرض في الرأس.


بشكل افتراضي، يعرض GroupDocs.Viewer اسم ملف الأرشيف في رأس كل صفحة. لتغيير هذا الاسم أو إخفائه، قم بتعيين هذه الخاصية.
لمزيد من المعلومات ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


يضبط اسم الملف الذي سيُعرض في الرأس.


بشكل افتراضي، يعرض GroupDocs.Viewer اسم ملف الأرشيف في رأس كل صفحة. لتغيير هذا الاسم أو إخفائه، قم بتعيين هذه الخاصية.
لمزيد من المعلومات ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | اسم الملف الذي سيتم عرضه. |
|

