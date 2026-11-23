---
title: "FileLogger"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Записывает сообщения журнала в файл."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Записывает сообщения журнала в файл.


Эта
FileLogger
класс предоставляет возможность записывать сообщения журнала в файл. Он реализует интерфейс ILogger
и может использоваться для регистрации различных событий и сообщений в приложении. Сообщения журнала записываются в указанный файл.


Пример использования:

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
класс предоставляет базовую функциональность журналирования.
Вы можете расширить этот класс, чтобы добавить пользовательские уровни журналирования или дополнительные функции журналирования в соответствии с вашими требованиями.*

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Создаёт журналировщик, который записывает сообщения в файл, указанный предоставленным именем файла. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Создаёт журналировщик, который записывает сообщения в файл с указанными уровнями журналирования. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Создаёт журналировщик, который записывает сообщения в файл, указанный предоставленным именем файла.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Полное имя файла с путём. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Создаёт журналировщик, который записывает сообщения в файл с указанными уровнями журналирования.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Полное имя файла с путём. |
|
|  | isTraceEnabled | boolean | Указывает, включено ли журналирование уровня trace. |
|
|  | isDebugEnabled | boolean | Указывает, включено ли журналирование уровня debug. |
|
|  | isWarningEnabled | boolean | Указывает, включено ли журналирование уровня warning. |
|
|  | isErrorEnabled | boolean | Указывает, включено ли журналирование уровня error. |
|

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
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


Проверяет, включён ли уровень трассировки для регистрации.


**Returns:**
boolean —  true  если уровень трассировки включён,  false  иначе.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
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
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


Проверяет, включён ли уровень отладки для регистрации.


**Returns:**
boolean —  true  если уровень отладки включён,  false  иначе.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
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
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


Проверяет, включён ли уровень предупреждений для регистрации.


**Returns:**
boolean —  true  если уровень предупреждения включён,  false  иначе.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
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
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


Проверяет, включена ли регистрация уровня ошибок.


**Returns:**
boolean —  true  если журналирование уровня ошибки включено,  false  иначе.

