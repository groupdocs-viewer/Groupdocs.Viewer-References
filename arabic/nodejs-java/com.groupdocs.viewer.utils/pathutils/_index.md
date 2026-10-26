---
title: "PathUtils"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "فئة PathUtils توفر طرقًا مساعدة للعمل مع مسارات الملفات."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

فئة PathUtils توفر طرقًا مساعدة للعمل مع مسارات الملفات.

تحتوي فئة PathUtils على طرق ثابتة تتيح لك إجراء عمليات مختلفة على مسارات الملفات في مكوّن GroupDocs.Viewer.

مثال على الاستخدام:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | اجمع أجزاء المسارات باستخدام الفاصل. |
| [getFileName(String path)](#getFileName-java.lang.String-) | يحصل على اسم الملف. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


اجمع أجزاء المسارات باستخدام الفاصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المعلمات | java.lang.String[] | أجزاء المسارات |

**Returns:**
java.lang.String - مسار النتيجة
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


يحصل على اسم الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار |

**Returns:**
java.lang.String - اسم الملف
