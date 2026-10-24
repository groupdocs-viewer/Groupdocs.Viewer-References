---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يتم إلقاء هذا الاستثناء عندما لا يتم العثور على ملف أو دليل."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

يُرمى هذا الاستثناء عندما لا يتم العثور على ملف أو دليل. وهو يشير إلى أن الملف أو الدليل المحدد غير موجود أو لا يمكن الوصول إليه.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | ينشئ مثلاً من فئة FileNotFoundException بالرسالة المحددة. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | يُنشئ مثلاً جديداً من فئة FileNotFoundException بمسار ملف محدد. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | ينشئ مثلاً جديداً من فئة FileNotFoundException برسالة خطأ محددة. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | يُنشئ مثلاً جديداً من فئة FileNotFoundException. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | يُنشئ مثلاً جديداً من فئة FileNotFoundException برسالة خطأ محددة. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


ينشئ مثلاً من فئة FileNotFoundException بالرسالة المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | الرسالة التي تصف الخطأ. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


يُنشئ مثلاً جديداً من فئة FileNotFoundException بمسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسار | java.nio.file.Path | مسار الملف غير الموجود. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


ينشئ مثلاً جديداً من فئة FileNotFoundException برسالة خطأ محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | الرسالة التي تصف الخطأ. |
|
|  | معلمات | java.lang.Object[] | المعلمات التي سيتم وضعها في رسالة الخطأ. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


يُنشئ مثلاً جديداً من فئة FileNotFoundException.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | السبب | java.lang.Throwable | سبب الاستثناء. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


يُنشئ مثلاً جديداً من فئة FileNotFoundException برسالة خطأ محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | الرسالة التي تصف الخطأ. |
|
|  | throwable | java.lang.Throwable | الـ throwable الذي تسبب في الاستثناء. |
|

