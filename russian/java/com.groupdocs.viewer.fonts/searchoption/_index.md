---
title: "SearchOption"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Указывает, искать ли в текущей папке или в текущей папке и всех подпапках."
type: docs
weight: 21
url: /ru/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Указывает, следует ли искать в текущей папке или в текущей папке и всех подпапках.


Перечисление SearchOption используется для указания области операции поиска шрифтов в API GroupDocs.Viewer.


Пример использования:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## Поля

| Поле | Описание |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Включает только текущую папку в поиск. |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | Включает текущую папку и все подпапки в поиск. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Включает только текущую папку в поиск.


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Включает текущую папку и все подпапки в поиск.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
