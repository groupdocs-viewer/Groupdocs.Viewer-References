---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "مسجل العرض العالمي."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

مسجل العرض العالمي.


ال
ViewerLogger
الفئة توفر وظائف لتسجيل الرسائل إلى مسجّل مدمج أو مسجّل معرف من قبل المستخدم.
تعمل كمسجّل عالمي لوحدة المشاهد ويمكن استخدامها لتسجيل أحداث ورسائل مختلفة.


مثال على الاستخدام:

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
يمكن تكوين الفئة لاستخدام تنفيذ مسجّل مخصص عن طريق استدعاء طريقة [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-).
بشكل افتراضي، يستخدم المسجّل المدمج المقدم من وحدة المشاهد.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | يكتب رسالة تتبع إلى وحدة التحكم. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تتبع إلى وحدة التحكم. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | يتحقق مما إذا كان مستوى التتبع مفعلاً للتسجيل. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تصحيح إلى وحدة التحكم. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تصحيح إلى وحدة التحكم. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | يتحقق مما إذا كان مستوى التصحيح مفعلاً للتسجيل. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تحذير إلى وحدة التحكم. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل تحذير إلى وحدة التحكم. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | يتحقق مما إذا كان مستوى التحذير مفعلاً للتسجيل. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل خطأ إلى وحدة التحكم. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | يكتب رسالة سجل خطأ إلى وحدة التحكم. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | يتحقق مما إذا كان تسجيل مستوى الخطأ مفعلاً. |
|
|  | [getLogger()](#getLogger--) | يحصل على نسخة المسجّل التي ستُستخدم لتسجيل الرسائل. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | يضبط نسخة المسجّل التي ستُستخدم لتسجيل الرسائل. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


يكتب رسالة تتبع إلى وحدة التحكم.
رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | رسالة التتبع. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب الإرسال. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تتبع إلى وحدة التحكم.
رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التتبع. |
|
|  | الرسالة | java.lang.String | رسالة سجل التتبع. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

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


يكتب رسالة سجل تصحيح إلى وحدة التحكم.
رسائل سجل التصحيح توفر معلومات حول عمليات مختلفة في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | رسالة سجل التصحيح. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تصحيح إلى وحدة التحكم.
رسائل سجل التصحيح توفر معلومات حول عمليات مختلفة في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التصحيح. |
|
|  | الرسالة | java.lang.String | رسالة سجل التصحيح. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

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


يكتب رسالة سجل تحذير إلى وحدة التحكم.
رسائل سجل التحذير توفر معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | رسالة سجل التحذير. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل تحذير إلى وحدة التحكم.
رسائل سجل التحذير توفر معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الاستثناء المرتبط برسالة سجل التحذير. |
|
|  | الرسالة | java.lang.String | رسالة سجل التحذير. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

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


يكتب رسالة سجل خطأ إلى وحدة التحكم.
رسائل سجل الخطأ توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الرسالة | java.lang.String | رسالة سجل الخطأ. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


يكتب رسالة سجل خطأ إلى وحدة التحكم.
رسائل سجل الخطأ توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | الاستثناء المرتبط برسالة سجل الخطأ. |
|
|  | الرسالة | java.lang.String | رسالة سجل الخطأ. |
|
|  | المعلمات | java.lang.Object[] | المعاملات التي سيتم استبدالها في الرسالة. ستستبدل العناصر النائبة {} بترتيب تمريرها. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


يتحقق مما إذا كان تسجيل مستوى الخطأ مفعلاً.


**Returns:**
منطقي -  true  إذا كان تسجيل الأخطاء مفعلاً،  false  خلاف ذلك.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


يحصل على نسخة المسجّل التي ستُستخدم لتسجيل الرسائل.
يمكن استخدام كائن السجل لتسجيل رسائل بمستويات مختلفة مثل التتبع، التصحيح، التحذير، والخطأ.


**Returns:**
com.groupdocs.foundation.logging.ILogger - كائن السجل.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


يضبط نسخة المسجّل التي ستُستخدم لتسجيل الرسائل.
يمكن استخدام كائن السجل لتسجيل رسائل بمستويات مختلفة مثل التتبع، التصحيح، التحذير، والخطأ.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسجل | com.groupdocs.foundation.logging.ILogger | كائن السجل لتعيينه. |
|

