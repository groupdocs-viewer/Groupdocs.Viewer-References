---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل مجلدًا يحتوي على خطوط TrueType."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

يمثل مجلدًا يحتوي على خطوط TrueType.

يتم استخدام فئة FolderFontSource لتحديد موقع مجلد يحتوي على خطوط TrueType. يسمح ذلك لواجهة برمجة تطبيقات GroupDocs.Viewer بالوصول إلى الخطوط المخزنة في المجلد المحدد لأغراض عرض المستند.

مثال على الاستخدام:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | يُنشئ نسخة جديدة من فئة  FolderFontSource  . |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | يحدد ما إذا كان كائنان  FolderFontSource  متطابقان. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | يحدد ما إذا كان كائنان  FolderFontSource  غير متطابقين. |
| [getFolderPath()](#getFolderPath--) | يحصل على المسار إلى المجلد الذي يحتوي على خطوط TrueType. |
| [getSearchOption()](#getSearchOption--) | يحصل على خيار البحث الذي يحدد ما إذا كان سيتم البحث في المجلد الحالي، أو في المجلد الحالي وجميع المجلدات الفرعية. |
| [isRecursive()](#isRecursive--) | يتحقق مما إذا كان سيتم البحث عن الخطوط بشكل متكرر. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | يحدد ما إذا كان كائن  FolderFontSource  الحالي هو نفسه كائن  FolderFontSource  المحدد. |
| [equals(Object o)](#equals-java.lang.Object-) | يحدد ما إذا كان كائن  FolderFontSource  الحالي هو نفسه الكائن المحدد. |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة (hash code) لكائن  FolderFontSource  الحالي. |
| [toString()](#toString--) | إرجاع سلسلة تمثل الكائن الحالي. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


يُنشئ نسخة جديدة من فئة  FolderFontSource  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| folderPath | java.lang.String | المسار إلى المجلد الذي يحتوي على خطوط TrueType. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | يحدد ما إذا كان سيتم البحث في المجلد الحالي، أو في المجلد الحالي وجميع المجلدات الفرعية. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


يحدد ما إذا كان كائنان  FolderFontSource  متطابقان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | كائن  FolderFontSource  الأيسر. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | كائن  FolderFontSource  الأيمن. |

**Returns:**
boolean -  true  إذا كان كلا كائني  FolderFontSource  متطابقين؛ وإلا،  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


يحدد ما إذا كان كائنان  FolderFontSource  غير متطابقين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | كائن  FolderFontSource  الأيسر. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | كائن  FolderFontSource  الأيمن. |

**Returns:**
boolean -  true  إذا كان كلا كائني  FolderFontSource  غير متطابقين؛ وإلا،  false .
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


يحصل على المسار إلى المجلد الذي يحتوي على خطوط TrueType.

**Returns:**
java.lang.String - المسار إلى المجلد الذي يحتوي على خطوط TrueType.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


يحصل على خيار البحث الذي يحدد ما إذا كان سيتم البحث في المجلد الحالي، أو في المجلد الحالي وجميع المجلدات الفرعية.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


يتحقق مما إذا كان سيتم البحث عن الخطوط بشكل متكرر.

**Returns:**
boolean -  true  إذا كان سيتم البحث عن الخطوط بشكل متكرر،  false  وإلا.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


يحدد ما إذا كان كائن  FolderFontSource  الحالي هو نفسه كائن  FolderFontSource  المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | الكائن للمقارنة مع كائن  FolderFontSource  الحالي. |

**Returns:**
boolean -  true  إذا كان كلا كائني  FolderFontSource  متطابقين؛ وإلا،  false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


يحدد ما إذا كان كائن  FolderFontSource  الحالي هو نفسه الكائن المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن للمقارنة مع كائن  FolderFontSource  الحالي. |

**Returns:**
boolean -  true  إذا كان المعامل  obj  من نوع  FolderFontSource  وهو نفسه كائن  FolderFontSource  الحالي؛ وإلا،  false
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز التجزئة (hash code) لكائن  FolderFontSource  الحالي.

**Returns:**
int - رمز تجزئة لكائن  FolderFontSource  الحالي.
### toString() {#toString--}
```
public String toString()
```


إرجاع سلسلة تمثل الكائن الحالي.

**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي.
