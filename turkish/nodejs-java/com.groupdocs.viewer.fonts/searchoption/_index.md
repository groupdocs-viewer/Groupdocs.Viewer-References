---
title: "SearchOption"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Geçerli klasörde veya geçerli klasörde ve tüm alt klasörlerde arama yapılıp yapılmayacağını belirtir."
type: docs
weight: 21
url: /tr/nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Geçerli klasörü mü yoksa geçerli klasörü ve tüm alt klasörleri mi arayacağını belirtir.

SearchOption enum'ı, GroupDocs.Viewer API'sinde yazı tipi arama işleminin kapsamını belirtmek için kullanılır.

Örnek kullanım:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Fields

| Field | Açıklama |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Aramada yalnızca geçerli klasörü içerir. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Aramada geçerli klasörü ve tüm alt klasörleri içerir. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Aramada yalnızca geçerli klasörü içerir.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Aramada geçerli klasörü ve tüm alt klasörleri içerir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
