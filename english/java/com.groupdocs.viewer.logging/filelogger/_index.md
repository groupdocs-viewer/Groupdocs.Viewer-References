---
title: FileLogger
second_title: GroupDocs.Viewer for Java API Reference
description: Writes log messages to a file.
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

Writes log messages to a file.

The  FileLogger  class provides functionality to write log messages to a file. It implements the ILogger interface and can be used to log various events and messages in an application. Log messages are written to the specified file.

Example usage:

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

Note: The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Creates a logger that logs messages to a file specified by the provided file name. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Creates a logger that logs messages to a file with specified logging levels. |
## Fields

| Field | Description |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methods

| Method | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Writes a trace message to the console. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a trace log message to the console. |
| [isTraceEnabled()](#isTraceEnabled--) | Checks if the trace level is enabled for logging. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Writes a debug log message to the console. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a debug log message to the console. |
| [isDebugEnabled()](#isDebugEnabled--) | Checks if the debug level is enabled for logging. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Writes a warning log message to the console. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes a warning log message to the console. |
| [isWarningEnabled()](#isWarningEnabled--) | Checks if the warning level is enabled for logging. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Writes an error log message to the console. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Writes an error log message to the console. |
| [isErrorEnabled()](#isErrorEnabled--) | Checks if error-level logging is enabled. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Creates a logger that logs messages to a file specified by the provided file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The full file name with path. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Creates a logger that logs messages to a file with specified logging levels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The full file name with path. |
| isTraceEnabled | boolean | Specifies whether trace level logging is enabled. |
| isDebugEnabled | boolean | Specifies whether debug level logging is enabled. |
| isWarningEnabled | boolean | Specifies whether warning level logging is enabled. |
| isErrorEnabled | boolean | Specifies whether error level logging is enabled. |

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


Writes a trace message to the console. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in order of passing. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Writes a trace log message to the console. Trace log messages provide generally useful information about the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception associated with the trace log message. |
| message | java.lang.String | The trace log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Checks if the trace level is enabled for logging.

**Returns:**
boolean -  true  if the trace level is enabled,  false  otherwise.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Writes a debug log message to the console. Debug log messages provide information about different processes in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The debug log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Writes a debug log message to the console. Debug log messages provide information about different processes in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception associated with the debug log message. |
| message | java.lang.String | The debug log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Checks if the debug level is enabled for logging.

**Returns:**
boolean -  true  if the debug level is enabled,  false  otherwise.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Writes a warning log message to the console. Warning log messages provide information about unexpected and recoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Writes a warning log message to the console. Warning log messages provide information about unexpected and recoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception associated with the warning log message. |
| message | java.lang.String | The warning log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Checks if the warning level is enabled for logging.

**Returns:**
boolean -  true  if the warning level is enabled,  false  otherwise.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Writes an error log message to the console. Error log messages provide information about unrecoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Writes an error log message to the console. Error log messages provide information about unrecoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | The exception associated with the error log message. |
| message | java.lang.String | The error log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Checks if error-level logging is enabled.

**Returns:**
boolean -  true  if error-level logging is enabled,  false  otherwise.
