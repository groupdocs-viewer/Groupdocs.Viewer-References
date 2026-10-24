---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحدد الإعدادات لتخصيص سلوك مكوّن Viewer."
type: docs
weight: 13
url: /ar/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

يحدد الإعدادات لتخصيص سلوك مكوّن Viewer.


فئة ViewerSettings توفر خيارات وخصائص لتخصيص سلوك مكوّن GroupDocs.Viewer أثناء عملية عرض المستند.
يمكنك استخدام هذه الفئة لتحديد إعدادات مختلفة، مثل المسجل، وتنفيذ ذاكرة تخزين مؤقت مخصص، وأكثر.


مثال على الاستخدام:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | ينشئ مثلاً جديداً من |
ViewerSettings
الفئة.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | ينشئ مثلاً جديداً من |
ViewerSettings
الفئة.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | ينشئ مثلاً جديداً من |
ViewerSettings
الفئة.
|
|  | [ViewerSettings()](#ViewerSettings--) | ينشئ مثلاً جديداً من |
ViewerSettings
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLogger()](#getLogger--) | يحصل على تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، التتبع). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | يضبط تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، التتبع). |
|
|  | [getCache()](#getCache--) | يحصل على تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج العرض. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | يضبط تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج العرض. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


ينشئ مثلاً جديداً من
ViewerSettings
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | الذاكرة المؤقتة. |
|
|  | مسجل | com.groupdocs.foundation.logging.ILogger | المسجل. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


ينشئ مثلاً جديداً من
ViewerSettings
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسجل | com.groupdocs.foundation.logging.ILogger | المسجل. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


ينشئ مثلاً جديداً من
ViewerSettings
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | الذاكرة المؤقتة. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


ينشئ مثلاً جديداً من
ViewerSettings
الفئة.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


يحصل على تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، التتبع).


**Returns:**
com.groupdocs.foundation.logging.ILogger - تنفيذ المسجل.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


يضبط تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، التتبع).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مسجل | com.groupdocs.foundation.logging.ILogger | تنفيذ المسجل المراد ضبطه. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


يحصل على تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج العرض.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


يضبط تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج العرض.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | تنفيذ التخزين المؤقت. |
|

