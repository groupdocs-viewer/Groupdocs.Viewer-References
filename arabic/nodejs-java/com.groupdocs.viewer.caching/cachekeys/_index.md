---
title: "CacheKeys"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر طرقًا لاسترجاع المعرف الفريد لمدخل الذاكرة المؤقتة."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

يوفر طرقًا لاسترجاع المعرف الفريد لمدخل الذاكرة المؤقتة.

تسمح لك الفئة بإنشاء مفاتيح التخزين المؤقت بناءً على معلمات مختلفة، مثل مسار المستند، خيارات العرض، واسم المورد. يمكن استخدام هذه المفاتيح لتخزين واسترجاع البيانات المؤقتة لتحسين كفاءة عرض المستند.

مثال على الاستخدام:

```

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAttachmentsKey()](#getAttachmentsKey--) | يعيد المعرف الفريد لمدخل التخزين المؤقت الذي يمثل مجموعة من كائنات [Attachment](../../com.groupdocs.viewer.results/attachment). |
| [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل ملف مرفق. |
| [getViewInfoKey()](#getViewInfoKey--) | يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل كائن [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
| [getFileInfoKey()](#getFileInfoKey--) | يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل كائن [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
| [getFileKey(String extension)](#getFileKey-java.lang.String-) | يسترجع المعرف الفريد لإدخال ذاكرة التخزين المؤقت الذي يمثل ملفًا. |
| [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | يسترجع المعرف الفريد لإدخال ذاكرة التخزين المؤقت الذي يمثل ملف صفحة. |
| [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | يرجع معرفًا فريدًا لإدخال ذاكرة التخزين المؤقت الذي يمثل كائن [Resource](../../com.groupdocs.viewer.results/resource). |
| [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | يرجع سلسلة تصفية للبحث عن إدخالات ذاكرة التخزين المؤقت التي تمثل كائنات [Resource](../../com.groupdocs.viewer.results/resource). |
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


يعيد المعرف الفريد لمدخل التخزين المؤقت الذي يمثل مجموعة من كائنات [Attachment](../../com.groupdocs.viewer.results/attachment).

**Returns:**
java.lang.String - المعرف الفريد لإدخال ذاكرة التخزين المؤقت للمرفقات.
### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل ملف مرفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| attachmentId | java.lang.String | المعرّف الفريد للمرفق (في سياق ملف واحد). |

**Returns:**
java.lang.String - المعرف الفريد لإدخال ذاكرة التخزين المؤقت لملف المرفق.
### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل كائن [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

**Returns:**
java.lang.String - المعرف الفريد لإدخال الذاكرة المؤقتة.
### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


يسترجع المعرف الفريد لمدخل التخزين المؤقت الذي يمثل كائن [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

**Returns:**
java.lang.String - المعرف الفريد لإدخال الذاكرة المؤقتة الذي يمثل كائن [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).
### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


يسترجع المعرف الفريد لإدخال ذاكرة التخزين المؤقت الذي يمثل ملفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الامتداد | java.lang.String | لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |

**Returns:**
java.lang.String - المعرف الفريد لمدخل التخزين المؤقت الذي يمثل ملفًا.
### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


يسترجع المعرف الفريد لإدخال ذاكرة التخزين المؤقت الذي يمثل ملف صفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber | int | عدد الصفحة. |
| الامتداد | java.lang.String | لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |

**Returns:**
java.lang.String - المعرف الفريد لمدخل التخزين المؤقت الذي يمثل ملف صفحة.
### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


يرجع معرفًا فريدًا لإدخال ذاكرة التخزين المؤقت الذي يمثل كائن [Resource](../../com.groupdocs.viewer.results/resource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber | int | عدد الصفحة. |
| resource | [Resource](../../com.groupdocs.viewer.results/resource) | مورد HTML. |

**Returns:**
java.lang.String - المعرف الفريد لإدخال الذاكرة المؤقتة.
### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


يرجع سلسلة تصفية للبحث عن إدخالات ذاكرة التخزين المؤقت التي تمثل كائنات [Resource](../../com.groupdocs.viewer.results/resource).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber | int | عدد الصفحة. |

**Returns:**
java.lang.String - سلسلة الفلتر للبحث عن مداخل التخزين المؤقت.
