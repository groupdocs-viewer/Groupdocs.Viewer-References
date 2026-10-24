---
title: "FileCache"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل ذاكرة مؤقتة محلية على القرص."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

يمثل ذاكرة مؤقتة محلية على القرص.


فئة FileCache تمثل ذاكرة مؤقتة محلية على القرص في مكوّن GroupDocs.Viewer.
توفر إمكانية تخزين واسترجاع البيانات المؤقتة على القرص لتصوير المستندات بكفاءة.


مثال على الاستخدام:

````

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
````


لاستخدام FileCache، تحتاج إلى إنشاء مثال من هذه الفئة وتمريره إلى كائن ViewerSettings.
سيستخدم كائن Viewer بعد ذلك FileCache لأغراض التخزين المؤقت أثناء تصوير المستندات.


***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer.
يمكنك أيضًا تنفيذ ذاكرة مؤقتة مخصصة خاصة بك عن طريق تنفيذ واجهة Cache.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | ينشئ مثالًا جديدًا من الـ |
FileCache
الفئة.
|
|  | [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | ينشئ مثالًا جديدًا من الـ |
FileCache
الفئة.
|
|  | [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | ينشئ مثالًا جديدًا من الـ |
FileCache
الفئة.
|
|  | [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | ينشئ مثالًا جديدًا من الـ |
FileCache
الفئة.
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCachePath()](#getCachePath--) | يحصل على المسار النسبي أو المطلق لمجلد الذاكرة المؤقتة. |
|
|  | [getCacheSubFolder()](#getCacheSubFolder--) | المجلد الفرعي لإضافته إلى مسار الذاكرة المؤقتة. |
|
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | يسلسل البيانات إلى القرص المحلي. |
|
|  | [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | يفك تسلسل البيانات المرتبطة بهذا المفتاح إذا كانت موجودة. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | يرجع جميع أسماء الملفات التي تحتوي على الفلتر في اسم الملف. |
|
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


ينشئ مثالًا جديدًا من الـ
FileCache
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cachePath | java.lang.String | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة المستند المؤقتة. |
|

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


ينشئ مثالًا جديدًا من الـ
FileCache
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة المستند المؤقتة. |
|

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


ينشئ مثالًا جديدًا من الـ
FileCache
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cachePath | java.lang.String | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة المستند المؤقتة. |
|
|  | cacheSubFolder | java.lang.String | المجلد الفرعي لإضافته إلى cachePath. |
|

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


ينشئ مثالًا جديدًا من الـ
FileCache
الفئة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cachePath | java.nio.file.Path | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة المستند المؤقتة. |
|
|  | cacheSubFolder | java.lang.String | المجلد الفرعي لإضافته إلى cachePath. |
|

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


يحصل على المسار النسبي أو المطلق لمجلد الذاكرة المؤقتة.


**Returns:**
java.lang.String - المسار إلى مجلد التخزين المؤقت.

### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


المجلد الفرعي لإضافته إلى مسار الذاكرة المؤقتة.


**Returns:**
java.lang.String - المجلد الفرعي للإضافة.

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


يسلسل البيانات إلى القرص المحلي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المفتاح | java.lang.String | المعرّف الفريد لمدخل التخزين المؤقت. |
|
|  | القيمة | java.lang.Object | الكائن المراد تسلسله. |
|

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


يفك تسلسل البيانات المرتبطة بهذا المفتاح إذا كانت موجودة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المفتاح | java.lang.String | مفتاح يحدد المدخل المطلوب. |
|
|  | clazz | java.lang.Class<T> | الفئة المتوقعة للقيمة. |
|

**Returns:**
T - القيمة الموجودة أو null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


يرجع جميع أسماء الملفات التي تحتوي على الفلتر في اسم الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المرشح | java.lang.String | المرشح للاستخدام. |
|

**Returns:**
java.util.List<java.lang.String> - أسماء الملفات التي تحتوي على المرشح في اسم الملف.

