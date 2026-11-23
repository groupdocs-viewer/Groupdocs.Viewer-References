---
title: "FileName"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل اسم ملف في الأرشيف."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

يمثل اسم ملف في الأرشيف.

تُغلف فئة FileName اسم الملف دون أي مسار أو معلومات دليل. توفر طرقًا للتعامل مع اسم الملف واسترجاع المعلومات المتعلقة به.

مثال على الاستخدام:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة  FileName . |
## الحقول

| حقل | الوصف |
| --- | --- |
| [EMPTY](#EMPTY) | يمثل اسم ملف فارغ. |
| [SOURCE](#SOURCE) | يمثل اسم ملف المصدر. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا للكائن الحالي. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


يُنشئ مثيلًا جديدًا من فئة  FileName .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


يمثل اسم ملف فارغ.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


يمثل اسم ملف المصدر.

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
