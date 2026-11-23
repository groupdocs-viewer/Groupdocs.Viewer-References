---
title: "FileLogger"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يكتب رسائل السجل إلى ملف."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

يكتب رسائل السجل إلى ملف.

توفر فئة  FileLogger  وظيفة كتابة رسائل السجل إلى ملف. تنفّذ واجهة ILogger ويمكن استخدامها لتسجيل أحداث ورسائل مختلفة في تطبيق. تُكتب رسائل السجل إلى الملف المحدد.

مثال على الاستخدام:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | ينشئ مسجلاً يسجل الرسائل إلى ملف محدد باسم الملف المقدم. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | ينشئ مسجلاً يسجل الرسائل إلى ملف بمستويات تسجيل محددة. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع إلى وحدة التحكم. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تتبع إلى وحدة التحكم. |
| [isTraceEnabled()](#isTraceEnabled--) | يتحقق مما إذا كان مستوى التتبع مفعلاً للتسجيل. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تصحيح إلى وحدة التحكم. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تصحيح إلى وحدة التحكم. |
| [isDebugEnabled()](#isDebugEnabled--) | يتحقق مما إذا كان مستوى التصحيح مفعلاً للتسجيل. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تحذير إلى وحدة التحكم. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تحذير إلى وحدة التحكم. |
| [isWarningEnabled()](#isWarningEnabled--) | يتحقق مما إذا كان مستوى التحذير مفعلاً للتسجيل. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل خطأ إلى وحدة التحكم. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل خطأ إلى وحدة التحكم. |
| [isErrorEnabled()](#isErrorEnabled--) | يتحقق مما إذا كان تسجيل الأخطاء مفعلاً. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


ينشئ مسجلاً يسجل الرسائل إلى ملف محدد باسم الملف المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف الكامل مع المسار. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


ينشئ مسجلاً يسجل الرسائل إلى ملف بمستويات تسجيل محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف الكامل مع المسار. |
| isTraceEnabled | boolean | يحدد ما إذا كان تسجيل مستوى التتبع مفعلاً. |
| isDebugEnabled | boolean | يحدد ما إذا كان تسجيل مستوى التصحيح مفعلاً. |
| isWarningEnabled | boolean | يحدد ما إذا كان تسجيل مستوى التحذير مفعلاً. |
| isErrorEnabled | boolean | يحدد ما إذا كان تسجيل مستوى الخطأ مفعلاً. |

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


يكتب رسالة تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التتبع. |
| معاملات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل \{\} وفقًا لترتيب المرور. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قابل للرمي | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التتبع. |
| رسالة | java.lang.String | رسالة سجل التتبع. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


يتحقق مما إذا كان مستوى التتبع مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التتبع مفعلاً،  false  خلاف ذلك.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


يكتب رسالة سجل تصحيح إلى وحدة التحكم. رسائل سجل التصحيح توفر معلومات حول عمليات مختلفة في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل التصحيح. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تصحيح إلى وحدة التحكم. رسائل سجل التصحيح توفر معلومات حول عمليات مختلفة في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قابل للرمي | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التصحيح. |
| رسالة | java.lang.String | رسالة سجل التصحيح. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


يتحقق مما إذا كان مستوى التصحيح مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التصحيح مفعلاً،  false  خلاف ذلك.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


يكتب رسالة سجل تحذير إلى وحدة التحكم. رسائل سجل التحذير توفر معلومات حول أحداث غير متوقعة وقابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل التحذير. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تحذير إلى وحدة التحكم. رسائل سجل التحذير توفر معلومات حول أحداث غير متوقعة وقابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قابل للرمي | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التحذير. |
| رسالة | java.lang.String | رسالة سجل التحذير. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


يتحقق مما إذا كان مستوى التحذير مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التحذير مفعلاً،  false  خلاف ذلك.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


يكتب رسالة سجل خطأ إلى وحدة التحكم. رسائل سجل الخطأ توفر معلومات حول أحداث غير قابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل الخطأ. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل خطأ إلى وحدة التحكم. رسائل سجل الخطأ توفر معلومات حول أحداث غير قابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قابل للرمي | java.lang.Throwable | الاستثناء المرتبط برسالة سجل الخطأ. |
| رسالة | java.lang.String | رسالة سجل الخطأ. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


يتحقق مما إذا كان تسجيل الأخطاء مفعلاً.

**Returns:**
منطقي -  true  إذا كان تسجيل الأخطاء مفعلاً،  false  خلاف ذلك.
