---
title: "ViewerLogger"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Глобальный логгер просмотрщика."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Глобальный логгер просмотрщика.


Эта
ViewerLogger
класс предоставляет возможность регистрировать сообщения в интегрированный или пользовательский регистратор.
Он служит глобальным регистратором для модуля viewer и может использоваться для регистрации различных событий и сообщений.


Пример использования:

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
класс можно настроить для использования пользовательской реализации регистратора, вызвав метод [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-).
По умолчанию он использует интегрированный регистратор, предоставляемый модулем viewer.*

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Записывает трассировочное сообщение в консоль. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает трассировочное лог‑сообщение в консоль. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Проверяет, включён ли уровень трассировки для регистрации. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Записывает отладочное лог‑сообщение в консоль. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает отладочное лог‑сообщение в консоль. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Проверяет, включён ли уровень отладки для регистрации. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Записывает предупреждающее лог‑сообщение в консоль. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает предупреждающее лог‑сообщение в консоль. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Проверяет, включён ли уровень предупреждений для регистрации. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в консоль. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Записывает сообщение об ошибке в консоль. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Проверяет, включена ли регистрация уровня ошибок. |
|
|  | [getLogger()](#getLogger--) | Получает экземпляр регистратора, который будет использоваться для регистрации сообщений. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Устанавливает экземпляр регистратора, который будет использоваться для регистрации сообщений. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Записывает трассировочное сообщение в консоль.
Трассировочные лог‑сообщения предоставляют общую полезную информацию о потоке выполнения приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Трассировочное сообщение. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке передачи. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


Записывает трассировочное лог‑сообщение в консоль.
Сообщения трассировки журнала предоставляют в целом полезную информацию о потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Исключение, связанное с сообщением трассировки журнала. |
|
|  | message | java.lang.String | Сообщение трассировки журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


Проверяет, включён ли уровень трассировки для регистрации.


**Returns:**
boolean —  true  если уровень трассировки включён,  false  иначе.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Записывает отладочное лог‑сообщение в консоль.
Сообщения отладки журнала предоставляют информацию о различных процессах в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение отладки журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


Записывает отладочное лог‑сообщение в консоль.
Сообщения отладки журнала предоставляют информацию о различных процессах в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Исключение, связанное с сообщением отладки журнала. |
|
|  | message | java.lang.String | Сообщение отладки журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


Проверяет, включён ли уровень отладки для регистрации.


**Returns:**
boolean —  true  если уровень отладки включён,  false  иначе.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Записывает предупреждающее лог‑сообщение в консоль.
Сообщения предупреждения журнала предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение предупреждения журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


Записывает предупреждающее лог‑сообщение в консоль.
Сообщения предупреждения журнала предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Исключение, связанное с сообщением предупреждения журнала. |
|
|  | message | java.lang.String | Сообщение предупреждения журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


Проверяет, включён ли уровень предупреждений для регистрации.


**Returns:**
boolean —  true  если уровень предупреждения включён,  false  иначе.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Записывает сообщение об ошибке в консоль.
Сообщения ошибок журнала предоставляют информацию о необратимых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | message | java.lang.String | Сообщение ошибки журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


Записывает сообщение об ошибке в консоль.
Сообщения ошибок журнала предоставляют информацию о необратимых событиях в потоке приложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Исключение, связанное с сообщением ошибки журнала. |
|
|  | message | java.lang.String | Сообщение ошибки журнала. |
|
|  | аргументы | java.lang.Object[] | Аргументы, которые будут заменены в сообщении. Они заменят заполнители {} в порядке их передачи. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


Проверяет, включена ли регистрация уровня ошибок.


**Returns:**
boolean —  true  если журналирование уровня ошибки включено,  false  иначе.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Получает экземпляр регистратора, который будет использоваться для регистрации сообщений.
Экземпляр логгера можно использовать для записи сообщений разных уровней, таких как трассировка, отладка, предупреждение и ошибка.


**Returns:**
com.groupdocs.foundation.logging.ILogger — экземпляр логгера.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Устанавливает экземпляр регистратора, который будет использоваться для регистрации сообщений.
Экземпляр логгера можно использовать для записи сообщений разных уровней, таких как трассировка, отладка, предупреждение и ошибка.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | логгер | com.groupdocs.foundation.logging.ILogger | Экземпляр логгера для установки. |
|

