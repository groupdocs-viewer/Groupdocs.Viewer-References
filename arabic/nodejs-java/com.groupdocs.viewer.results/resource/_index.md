---
title: "Resource"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

يمثل مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات.

تمثل فئة Resource موردًا يُستخدم في عرض HTML في مكوّن GroupDocs.Viewer. يمكنها تمثيل أنواع مختلفة من الموارد، مثل الخطوط والأنماط والصور أو الرسومات، التي يتم تضمينها أو الإشارة إليها في مخرجات HTML المُولدة أثناء عملية العرض.

مثال على الاستخدام:

```

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | ينشئ مثيلاً جديدًا من الفئة Resource. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFileName()](#getFileName--) | يعيد اسم الملف الخاص بالمورد. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | يضبط اسم الملف الخاص بالمورد. |
| [isNested()](#isNested--) | يعيد ما إذا كان المورد موجودًا داخل مورد آخر، مثل مورد خط موجود داخل مورد CSS أو SVG. |
| [setNested(boolean nested)](#setNested-boolean-) | يضبط ما إذا كان المورد موجودًا داخل مورد آخر. |
| [toString()](#toString--) | إرجاع سلسلة تمثل الكائن الحالي. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


ينشئ مثيلاً جديدًا من الفئة Resource.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم ملف المورد. |
| متداخل | boolean | يشير إلى ما إذا كان المورد موجودًا داخل مورد آخر، مثل مورد خط موجود داخل مورد CSS أو SVG. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


يعيد اسم الملف الخاص بالمورد.

**Returns:**
java.lang.String - اسم ملف المورد.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


يضبط اسم الملف الخاص بالمورد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف الجديد للمورد. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


يعيد ما إذا كان المورد موجودًا داخل مورد آخر، مثل مورد خط موجود داخل مورد CSS أو SVG.

**Returns:**
boolean - ما إذا كان المورد موجودًا داخل مورد آخر.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


يضبط ما إذا كان المورد موجودًا داخل مورد آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| متداخل | boolean | ما إذا كان يجب ضبط المورد كمتداخل. |

### toString() {#toString--}
```
public String toString()
```


إرجاع سلسلة تمثل الكائن الحالي.

**Returns:**
java.lang.String - تمثيل النص للكائن الحالي.
