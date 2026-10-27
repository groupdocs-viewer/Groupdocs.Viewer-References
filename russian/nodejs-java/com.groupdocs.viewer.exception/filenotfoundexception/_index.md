---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Это исключение выбрасывается, когда файл или каталог не найден."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

Это исключение выбрасывается, когда файл или каталог не найден. Оно указывает, что указанный файл или каталог не существует или к нему нельзя получить доступ.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | Создает экземпляр класса FileNotFoundException с указанным сообщением. |
| [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | Инициализирует новый экземпляр класса FileNotFoundException с указанным путем к файлу. |
| [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | Создает новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке. |
| [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | Создает новый экземпляр класса FileNotFoundException. |
| [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | Инициализирует новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке. |
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


Создает экземпляр класса FileNotFoundException с указанным сообщением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, описывающее ошибку. |

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


Инициализирует новый экземпляр класса FileNotFoundException с указанным путем к файлу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| путь | java.nio.file.Path | Путь к файлу, который не существует. |

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


Создает новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| messageTemplate | java.lang.String | Сообщение, описывающее ошибку. |
| params | java.lang.Object[] | Параметры, которые будут подставлены в сообщение об ошибке. |

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


Создает новый экземпляр класса FileNotFoundException.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| причина | java.lang.Throwable | Причина исключения. |

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


Инициализирует новый экземпляр класса FileNotFoundException с указанным сообщением об ошибке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, описывающее ошибку. |
| исключаемый объект | java.lang.Throwable | Исключаемый объект, вызвавший исключение. |

