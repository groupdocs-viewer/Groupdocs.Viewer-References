---
title: FileLogger
second_title: GroupDocs.Viewer for Java API Reference
description: Writes log messages to the file.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Writes log messages to the file.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Create logger to file. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Create logger to file. |
## Methods

| Method | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Writes a trace message to the console. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a trace message to the console. |
| [isTraceEnabled()](#isTraceEnabled--) |  |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Writes a debug message to the console. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a debug message to the console. |
| [isDebugEnabled()](#isDebugEnabled--) |  |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Writes a warning message to the console. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a warning message to the console. |
| [isWarningEnabled()](#isWarningEnabled--) |  |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Writes an error message to the console. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes an error message to the console. |
| [isErrorEnabled()](#isErrorEnabled--) |  |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Create logger to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Full file name with path |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Create logger to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |
| isTraceEnabled | boolean |  |
| isDebugEnabled | boolean |  |
| isWarningEnabled | boolean |  |
| isErrorEnabled | boolean |  |

### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Writes a trace message to the console. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Writes a trace message to the console. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception |
| message | java.lang.String | The trace message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Checks is trace logging enabled

**Returns:**
boolean
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Writes a debug message to the console. Debug log messages provide information about different processes in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The debug message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Writes a debug message to the console. Debug log messages provide information about different processes in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception |
| message | java.lang.String | The debug message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Checks is debug logging enabled

**Returns:**
boolean
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Writes a warning message to the console. Warning log messages provide information about unexpected and recoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Writes a warning message to the console. Warning log messages provide information about unexpected and recoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception |
| message | java.lang.String | The warning message. |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Checks is warning logging enabled

**Returns:**
boolean
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Writes an error message to the console. Error log messages provide information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Writes an error message to the console. Error log messages provide information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception |
| message | java.lang.String | The error message |
| arguments | java.lang.Object[] | The arguments, replaces \{\} in message in order of passing |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Checks is error logging enabled

**Returns:**
boolean
