---
title: "SearchOption"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحدد ما إذا كان سيتم البحث في المجلد الحالي أو المجلد الحالي وجميع المجلدات الفرعية."
type: docs
weight: 21
url: /ar/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

يحدد ما إذا كان يجب البحث في المجلد الحالي، أو المجلد الحالي وجميع المجلدات الفرعية.

يتم استخدام تعداد SearchOption لتحديد نطاق عملية البحث عن الخطوط في واجهة برمجة تطبيقات GroupDocs.Viewer API.

مثال على الاستخدام:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## الحقول

| حقل | الوصف |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | يتضمن فقط المجلد الحالي في البحث. |
| [ALL_FOLDERS](#ALL-FOLDERS) | يتضمن المجلد الحالي وجميع المجلدات الفرعية في البحث. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


يتضمن فقط المجلد الحالي في البحث.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


يتضمن المجلد الحالي وجميع المجلدات الفرعية في البحث.

### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
