---
title: "FileName"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل اسم ملف في الأرشيف."
type: docs
weight: 15
url: /ar/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

يمثل اسم ملف في الأرشيف.


فئة FileName تغلف اسم الملف دون أي مسار أو معلومات دليل.
توفر طرقًا للتلاعب واسترجاع المعلومات حول اسم الملف.


مثال على الاستخدام:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | ينشئ مثلاً جديداً من |
FileName
الفئة.
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [EMPTY](#EMPTY) | يمثل اسم ملف فارغ. |
|
|  | [SOURCE](#SOURCE) | يمثل اسم الملف المصدر. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | يرجع تمثيلًا نصيًا للكائن الحالي. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


ينشئ مثلاً جديداً من
FileName
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileName | java.lang.String | اسم الملف. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


يمثل اسم ملف فارغ.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


يمثل اسم الملف المصدر.


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا للكائن الحالي.


**Returns:**
java.lang.String - تمثيل نصي للكائن الحالي.

