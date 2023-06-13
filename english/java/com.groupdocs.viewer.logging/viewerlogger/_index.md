---
title: ViewerLogger
second_title: GroupDocs.Viewer for Java API Reference
description: Global viewer logger.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Global viewer logger.

The  ViewerLogger  class provides functionality to log messages to an integrated or user-defined logger. It serves as the global logger for the viewer module and can be used to log various events and messages.

Example usage:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

Note: The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.
## Constructors

| Constructor | Description |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | Gets the logger instance that will be used for logging messages. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Sets the logger instance that will be used for logging messages. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Writes a trace message to the console. Trace log messages provide generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in order of passing. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


Checks if the trace level is enabled for logging.

**Returns:**
boolean -  true  if the trace level is enabled,  false  otherwise.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Writes a debug log message to the console. Debug log messages provide information about different processes in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The debug log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Checks if the debug level is enabled for logging.

**Returns:**
boolean -  true  if the debug level is enabled,  false  otherwise.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Writes a warning log message to the console. Warning log messages provide information about unexpected and recoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Checks if the warning level is enabled for logging.

**Returns:**
boolean -  true  if the warning level is enabled,  false  otherwise.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Writes an error log message to the console. Error log messages provide information about unrecoverable events in the application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error log message. |
| arguments | java.lang.Object[] | The arguments to be replaced in the message. They will replace \{\} placeholders in the order they are passed. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Checks if error-level logging is enabled.

**Returns:**
boolean -  true  if error-level logging is enabled,  false  otherwise.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Gets the logger instance that will be used for logging messages. The logger instance can be used to log messages of different levels such as trace, debug, warning, and error.

**Returns:**
com.groupdocs.foundation.logging.ILogger - the logger instance.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Sets the logger instance that will be used for logging messages. The logger instance can be used to log messages of different levels such as trace, debug, warning, and error.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | The logger instance to set. |

