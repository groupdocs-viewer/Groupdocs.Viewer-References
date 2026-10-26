---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "مسجل عارض عالمي."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

مسجل عارض عالمي.

فئة ViewerLogger توفر وظيفة تسجيل الرسائل إلى مسجّل مدمج أو مخصص من قبل المستخدم. تعمل كمسجّل عالمي لوحدة المشاهد ويمكن استخدامها لتسجيل أحداث ورسائل مختلفة.

مثال على الاستخدام:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | يحصل على نسخة المسجّل التي ستُستخدم لتسجيل الرسائل. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | يضبط نسخة المسجّل التي ستُستخدم لتسجيل الرسائل. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


يكتب رسالة تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التتبع. |
| معاملات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل \{\} وفقًا لترتيب المرور. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


يتحقق مما إذا كان مستوى التتبع مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التتبع مفعلاً،  false  خلاف ذلك.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


يكتب رسالة سجل تصحيح إلى وحدة التحكم. رسائل سجل التصحيح توفر معلومات حول عمليات مختلفة في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل التصحيح. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


يتحقق مما إذا كان مستوى التصحيح مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التصحيح مفعلاً،  false  خلاف ذلك.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


يكتب رسالة سجل تحذير إلى وحدة التحكم. رسائل سجل التحذير توفر معلومات حول أحداث غير متوقعة وقابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل التحذير. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


يتحقق مما إذا كان مستوى التحذير مفعلاً للتسجيل.

**Returns:**
منطقي -  true  إذا كان مستوى التحذير مفعلاً،  false  خلاف ذلك.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


يكتب رسالة سجل خطأ إلى وحدة التحكم. رسائل سجل الخطأ توفر معلومات حول أحداث غير قابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة سجل الخطأ. |
| معاملات | java.lang.Object[] | المعلمات التي سيتم استبدالها في الرسالة. ستستبدل نواقل \{\} بالترتيب الذي يتم تمريره. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


يتحقق مما إذا كان تسجيل الأخطاء مفعلاً.

**Returns:**
منطقي -  true  إذا كان تسجيل الأخطاء مفعلاً،  false  خلاف ذلك.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


يحصل على كائن السجل الذي سيُستخدم لتسجيل الرسائل. يمكن استخدام كائن السجل لتسجيل رسائل بمستويات مختلفة مثل التتبع، التصحيح، التحذير، والخطأ.

**Returns:**
com.groupdocs.foundation.logging.ILogger - كائن السجل.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


يضبط كائن السجل الذي سيُستخدم لتسجيل الرسائل. يمكن استخدام كائن السجل لتسجيل رسائل بمستويات مختلفة مثل التتبع، التصحيح، التحذير، والخطأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | كائن السجل لتعيينه. |

