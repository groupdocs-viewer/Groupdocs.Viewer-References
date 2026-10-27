---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Глобальный журнал просмотрщика."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Глобальный журнал просмотрщика.

Класс ViewerLogger предоставляет возможность записывать сообщения в интегрированный или пользовательский регистратор. Он служит глобальным регистратором для модуля просмотра и может использоваться для записи различных событий и сообщений.

Пример использования:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | Получает экземпляр логгера, который будет использоваться для записи сообщений. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Устанавливает экземпляр логгера, который будет использоваться для записи сообщений. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Записывает трассировочное сообщение в консоль. Трассировочные сообщения обычно предоставляют полезную информацию о ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Трассировочное сообщение. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке передачи. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


Проверяет, включён ли уровень трассировки для логирования.

**Returns:**
boolean -  true  если уровень трассировки включён,  false  в противном случае.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Записывает сообщение отладки в консоль. Сообщения отладки предоставляют информацию о различных процессах в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение отладки. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Проверяет, включён ли уровень отладки для логирования.

**Returns:**
boolean -  true  если уровень отладки включён,  false  в противном случае.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Записывает сообщение предупреждения в консоль. Сообщения предупреждения предоставляют информацию о неожиданных и восстанавливаемых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение предупреждения. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Проверяет, включён ли уровень предупреждений для логирования.

**Returns:**
boolean -  true  если уровень предупреждения включён,  false  в противном случае.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Записывает сообщение об ошибке в консоль. Сообщения об ошибке предоставляют информацию о необратимых событиях в ходе выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке. |
| аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители \{\} в порядке их передачи. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Проверяет, включено ли логирование уровня ошибок.

**Returns:**
boolean -  true  если журналирование уровня ошибки включено,  false  в противном случае.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Получает экземпляр логгера, который будет использоваться для записи сообщений. Экземпляр логгера может использоваться для записи сообщений разных уровней, таких как трассировка, отладка, предупреждение и ошибка.

**Returns:**
com.groupdocs.foundation.logging.ILogger — экземпляр логгера.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Устанавливает экземпляр логгера, который будет использоваться для записи сообщений. Экземпляр логгера может использоваться для записи сообщений разных уровней, таких как трассировка, отладка, предупреждение и ошибка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Экземпляр логгера для установки. |

