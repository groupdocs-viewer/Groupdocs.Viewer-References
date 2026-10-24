---
title: "SearchOption"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Menentukan apakah akan mencari di folder saat ini atau di folder saat ini dan semua subfolder."
type: docs
weight: 21
url: /id/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Menentukan apakah akan mencari di folder saat ini, atau di folder saat ini dan semua subfolder.


Enum SearchOption digunakan untuk menentukan ruang lingkup operasi pencarian font dalam API GroupDocs.Viewer.


Contoh penggunaan:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Menyertakan hanya folder saat ini dalam pencarian. |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | Menyertakan folder saat ini dan semua subfolder dalam pencarian. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Menyertakan hanya folder saat ini dalam pencarian.


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Menyertakan folder saat ini dan semua subfolder dalam pencarian.


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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
