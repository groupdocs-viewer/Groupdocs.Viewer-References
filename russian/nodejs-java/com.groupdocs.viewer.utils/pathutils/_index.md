---
title: "PathUtils"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Класс PathUtils предоставляет утилитные методы для работы с файловыми путями."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Класс PathUtils предоставляет утилитные методы для работы с файловыми путями.

Класс PathUtils содержит статические методы, позволяющие выполнять различные операции с файловыми путями в компоненте GroupDocs.Viewer.

Пример использования:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Методы

| Метод | Описание |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Объединяет части путей, используя разделитель. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Получает имя файла. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Объединяет части путей, используя разделитель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| params | java.lang.String[] | части путей |

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
| путь | java.lang.String | путь |

**Returns:**
java.lang.String - имя файла
