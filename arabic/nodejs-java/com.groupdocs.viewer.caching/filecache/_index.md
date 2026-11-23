---
title: "FileCache"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل ذاكرة مؤقتة محلية على القرص."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

يمثل ذاكرة مؤقتة محلية على القرص.

فئة FileCache تمثل مخزنًا محليًا على القرص في مكوّن GroupDocs.Viewer. توفر وظيفة لتخزين واسترجاع البيانات المخزنة مؤقتًا على القرص من أجل عرض المستندات بكفاءة.

مثال على الاستخدام:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

لاستخدام FileCache، تحتاج إلى إنشاء مثيل من هذه الفئة وتمريره إلى كائن ViewerSettings. سيستخدم كائن Viewer بعد ذلك FileCache لأغراض التخزين المؤقت أثناء عرض المستندات.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | ينشئ مثيلًا جديدًا من فئة FileCache. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | ينشئ مثيلًا جديدًا من فئة FileCache. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | ينشئ مثيلًا جديدًا من فئة FileCache. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | ينشئ مثيلًا جديدًا من فئة FileCache. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCachePath()](#getCachePath--) | يحصل على المسار النسبي أو المطلق لمجلد التخزين المؤقت. |
| [getCacheSubFolder()](#getCacheSubFolder--) | المجلد الفرعي لإضافته إلى مسار التخزين المؤقت. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | يقوم بتسلسل البيانات إلى القرص المحلي. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | يقوم بفك تسلسل البيانات المرتبطة بهذا المفتاح إذا كانت موجودة. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | يعيد جميع أسماء الملفات التي تحتوي على الفلتر في اسم الملف. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


ينشئ مثيلًا جديدًا من فئة FileCache.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cachePath | java.lang.String | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


ينشئ مثيلًا جديدًا من فئة FileCache.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cachePath | java.nio.file.Path | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


ينشئ مثيلًا جديدًا من فئة FileCache.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cachePath | java.lang.String | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |
| cacheSubFolder | java.lang.String | المجلد الفرعي لإضافته إلى cachePath. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


ينشئ مثيلًا جديدًا من فئة FileCache.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cachePath | java.nio.file.Path | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |
| cacheSubFolder | java.lang.String | المجلد الفرعي لإضافته إلى cachePath. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


يحصل على المسار النسبي أو المطلق لمجلد التخزين المؤقت.

**Returns:**
java.lang.String - المسار إلى مجلد الذاكرة المؤقتة.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


المجلد الفرعي لإضافته إلى مسار التخزين المؤقت.

**Returns:**
java.lang.String - المجلد الفرعي لإضافته.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


يقوم بتسلسل البيانات إلى القرص المحلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | المعرّف الفريد لمدخل الذاكرة المؤقتة. |
| value | java.lang.Object | الكائن لتسلسله. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


يقوم بفك تسلسل البيانات المرتبطة بهذا المفتاح إذا كانت موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key | java.lang.String | مفتاح يحدد المدخل المطلوب. |
| clazz | java.lang.Class<T> | الفئة للقيمة المتوقعة. |

**Returns:**
T - القيمة الموجودة أو null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


يعيد جميع أسماء الملفات التي تحتوي على الفلتر في اسم الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filter | java.lang.String | الفلتر للاستخدام. |

**Returns:**
java.util.List<java.lang.String> - أسماء الملفات التي تحتوي على الفلتر في اسم الملف.
