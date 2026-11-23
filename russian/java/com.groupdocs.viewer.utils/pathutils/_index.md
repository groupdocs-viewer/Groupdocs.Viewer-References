---
title: "PathUtils"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Класс PathUtils предоставляет вспомогательные методы для работы с файловыми путями."
type: docs
weight: 13
url: /ru/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Класс PathUtils предоставляет вспомогательные методы для работы с файловыми путями.


Класс PathUtils содержит статические методы, которые позволяют выполнять различные операции
с путями к файлам в компоненте GroupDocs.Viewer.


Пример использования:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## Методы

| Метод | Описание |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | Объединяйте части путей, используя разделитель. |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | Получает имя файла. |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Объединяйте части путей, используя разделитель.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | params | java.lang.String[] | части путей |
|

**Returns:**
java.lang.String - результирующий путь

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Получает имя файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | путь | java.lang.String | путь |
|

**Returns:**
java.lang.String - имя файла

