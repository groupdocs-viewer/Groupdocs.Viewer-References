---
title: "FileLogger"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Записывает сообщения журнала в файл."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Записывает сообщения журнала в файл.

Класс  FileLogger  предоставляет возможность записывать сообщения журнала в файл. Он реализует интерфейс ILogger и может использоваться для записи различных событий и сообщений в приложении. Сообщения журнала записываются в указанный файл.

Пример использования:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Создает журнал, который записывает сообщения в файл, указанный предоставленным именем файла. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Создает журнал, который записывает сообщения в файл с указанными уровнями журналирования. |
## Поля

| Поле | Описание |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение в консоль. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает трассировочное лог‑сообщение в консоль. |
| [isTraceEnabled()](#isTraceEnabled--) | Проверяет, включён ли уровень трассировки для логирования. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Записывает отладочное лог‑сообщение в консоль. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает отладочное лог‑сообщение в консоль. |
| [isDebugEnabled()](#isDebugEnabled--) | Проверяет, включён ли уровень отладки для логирования. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Записывает предупреждающее лог‑сообщение в консоль. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает предупреждающее лог‑сообщение в консоль. |
| [isWarningEnabled()](#isWarningEnabled--) | Проверяет, включён ли уровень предупреждений для логирования. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в консоль. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в консоль. |
| [isErrorEnabled()](#isErrorEnabled--) | Проверяет, включено ли логирование уровня ошибок. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Создает журнал, который записывает сообщения в файл, указанный предоставленным именем файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Полное имя файла с путем. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Создает журнал, который записывает сообщения в файл с указанными уровнями журналирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Полное имя файла с путем. |
| isTraceEnabled | boolean | Указывает, включено ли журналирование уровня trace. |
| isDebugEnabled | boolean | Указывает, включено ли журналирование уровня debug. |
| isWarningEnabled | boolean | Указывает, включено ли журналирование уровня warning. |
| isErrorEnabled | boolean | Указывает, включено ли журналирование уровня error. |

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Записывает трассировочное сообщение в консоль. Трассировочные сообщения обычно предоставляют полезную информацию о ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Трассировочное сообщение. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке передачи. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение трассировки в консоль. Сообщения трассировки предоставляют обычно полезную информацию о ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исключаемый объект | java.lang.Throwable | Исключение, связанное с сообщением трассировки. |
| сообщение | java.lang.String | Сообщение трассировки. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Проверяет, включён ли уровень трассировки для логирования.

**Returns:**
boolean -  true  если уровень трассировки включён,  false  в противном случае.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Записывает сообщение отладки в консоль. Сообщения отладки предоставляют информацию о различных процессах в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение отладки. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение отладки в консоль. Сообщения отладки предоставляют информацию о различных процессах в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исключаемый объект | java.lang.Throwable | Исключение, связанное с сообщением отладки. |
| сообщение | java.lang.String | Сообщение отладки. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Проверяет, включён ли уровень отладки для логирования.

**Returns:**
boolean -  true  если уровень отладки включён,  false  в противном случае.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Записывает сообщение предупреждения в консоль. Сообщения предупреждения предоставляют информацию о неожиданных и восстанавливаемых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение предупреждения. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение предупреждения в консоль. Сообщения предупреждения предоставляют информацию о неожиданных и восстанавливаемых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исключаемый объект | java.lang.Throwable | Исключение, связанное с сообщением предупреждения. |
| сообщение | java.lang.String | Сообщение предупреждения. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Проверяет, включён ли уровень предупреждений для логирования.

**Returns:**
boolean -  true  если уровень предупреждения включён,  false  в противном случае.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Записывает сообщение об ошибке в консоль. Сообщения об ошибке предоставляют информацию о необратимых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение об ошибке в консоль. Сообщения об ошибке предоставляют информацию о необратимых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исключаемый объект | java.lang.Throwable | Исключение, связанное с сообщением об ошибке. |
| сообщение | java.lang.String | Сообщение об ошибке. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Проверяет, включено ли логирование уровня ошибок.

**Returns:**
boolean -  true  если журналирование уровня ошибки включено,  false  в противном случае.
