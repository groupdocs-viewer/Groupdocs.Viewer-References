---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يتم إلقاء هذا الاستثناء عندما لا يتم العثور على ملف أو دليل."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

يتم إلقاء هذا الاستثناء عندما لا يتم العثور على ملف أو دليل. يشير إلى أن الملف أو الدليل المحدد غير موجود أو لا يمكن الوصول إليه.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | ينشئ مثيلاً لفئة FileNotFoundException مع الرسالة المحددة. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | يُهيئ مثيلاً جديدًا لفئة FileNotFoundException بمسار ملف محدد. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | ينشئ مثيلاً جديدًا لفئة FileNotFoundException برسالة خطأ محددة. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | ينشئ مثيلاً جديدًا لفئة FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | يُهيئ مثيلاً جديدًا لفئة FileNotFoundException برسالة خطأ محددة. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


ينشئ مثيلاً لفئة FileNotFoundException مع الرسالة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | الرسالة التي تصف الخطأ. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


يُهيئ مثيلاً جديدًا لفئة FileNotFoundException بمسار ملف محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.nio.file.Path | مسار الملف الذي لا وجود له. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


ينشئ مثيلاً جديدًا لفئة FileNotFoundException برسالة خطأ محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| messageTemplate | java.lang.String | الرسالة التي تصف الخطأ. |
| المعلمات | java.lang.Object[] | المعلمات التي سيتم تعيينها في رسالة الخطأ. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


ينشئ مثيلاً جديدًا لفئة FileNotFoundException.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| سبب | java.lang.Throwable | سبب الاستثناء. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


يُهيئ مثيلاً جديدًا لفئة FileNotFoundException برسالة خطأ محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | الرسالة التي تصف الخطأ. |
| قابل للرمي | java.lang.Throwable | الكائن القابل للرمي الذي تسبب في الاستثناء. |

