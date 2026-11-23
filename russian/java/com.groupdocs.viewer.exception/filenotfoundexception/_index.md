---
title: "FileNotFoundException"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Это исключение выбрасывается, когда файл или каталог не найден."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Это исключение выбрасывается, когда файл или каталог не найден. Оно указывает, что указанный файл или каталог не существует или недоступен.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Создаёт экземпляр класса FileNotFoundException с указанным сообщением. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Инициализирует новый экземпляр класса FileNotFoundException с указанным путём к файлу. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Создаёт новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Создаёт новый экземпляр класса FileNotFoundException. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Создаёт экземпляр класса FileNotFoundException с указанным сообщением.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, описывающее ошибку. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Инициализирует новый экземпляр класса FileNotFoundException с указанным путём к файлу.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | путь | java.nio.file.Path | Путь к файлу, который не существует. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Создаёт новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | Сообщение, описывающее ошибку. |
|
|  | params | java.lang.Object[] | Параметры, которые будут подставлены в сообщение об ошибке. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Создаёт новый экземпляр класса FileNotFoundException.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | причина | java.lang.Throwable | Причина исключения. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Инициализирует новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение, описывающее ошибку. |
|
|  | throwable | java.lang.Throwable | Объект throwable, вызвавший исключение. |
|

