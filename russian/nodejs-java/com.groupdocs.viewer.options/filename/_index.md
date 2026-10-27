---
title: "FileName"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет имя файла в архиве."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Представляет имя файла в архиве.

Класс FileName инкапсулирует имя файла без какой-либо информации о пути или каталоге. Он предоставляет методы для манипулирования и получения информации об имени файла.

Пример использования:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | Инициализирует новый экземпляр класса  FileName . |
## Поля

| Поле | Описание |
| --- | --- |
| [EMPTY](#EMPTY) | Представляет пустое имя файла. |
| [SOURCE](#SOURCE) | Представляет имя исходного файла. |
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Возвращает строковое представление текущего объекта. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Инициализирует новый экземпляр класса  FileName .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Представляет пустое имя файла.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Представляет имя исходного файла.

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление текущего объекта.

**Returns:**
java.lang.String — строковое представление текущего объекта.
