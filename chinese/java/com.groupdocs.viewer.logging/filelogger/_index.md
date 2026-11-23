---
title: "FileLogger"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "将日志消息写入文件。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

将日志消息写入文件。


该
FileLogger
类提供将日志消息写入文件的功能。它实现了 ILogger 接口。
并且可用于记录应用程序中的各种事件和消息。日志消息会写入指定的文件。


示例用法：

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
类提供基本的日志功能。
您可以扩展此类，以根据您的需求添加自定义日志级别或其他日志功能。*

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | 创建一个记录器，将日志消息记录到由提供的文件名指定的文件中。 |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 创建一个记录器，将日志消息记录到具有指定日志级别的文件中。 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 将跟踪消息写入控制台。 |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将跟踪日志消息写入控制台。 |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 检查是否已启用跟踪级别的日志记录。 |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 将调试日志消息写入控制台。 |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将调试日志消息写入控制台。 |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 检查是否已启用调试级别的日志记录。 |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 将警告日志消息写入控制台。 |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将警告日志消息写入控制台。 |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 检查是否已启用警告级别的日志记录。 |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 将错误日志消息写入控制台。 |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 将错误日志消息写入控制台。 |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 检查是否已启用错误级别的日志记录。 |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


创建一个记录器，将日志消息记录到由提供的文件名指定的文件中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileName | java.lang.String | 完整的带路径的文件名。 |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


创建一个记录器，将日志消息记录到具有指定日志级别的文件中。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fileName | java.lang.String | 完整的带路径的文件名。 |
|
|  | isTraceEnabled | boolean | 指定是否启用跟踪级别的日志记录。 |
|
|  | isDebugEnabled | boolean | 指定是否启用调试级别的日志记录。 |
|
|  | isWarningEnabled | boolean | 指定是否启用警告级别的日志记录。 |
|
|  | isErrorEnabled | boolean | 指定是否启用错误级别的日志记录。 |
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


将跟踪消息写入控制台。
跟踪日志消息提供有关应用程序流程的一般有用信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 跟踪消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传入顺序替换 {} 占位符。 |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


将跟踪日志消息写入控制台。
跟踪日志消息提供有关应用程序流程的一般有用信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 异常对象 | java.lang.Throwable | 与跟踪日志消息关联的异常。 |
|
|  | 消息 | java.lang.String | 跟踪日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


检查是否已启用跟踪级别的日志记录。


**Returns:**
布尔型 - 如果启用了跟踪级别则为 true，否则为 false。

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


将调试日志消息写入控制台。
调试日志消息提供有关应用程序流程中不同过程的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 调试日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


将调试日志消息写入控制台。
调试日志消息提供有关应用程序流程中不同过程的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 异常对象 | java.lang.Throwable | 与调试日志消息关联的异常。 |
|
|  | 消息 | java.lang.String | 调试日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


检查是否已启用调试级别的日志记录。


**Returns:**
布尔型 - 如果启用了调试级别则为 true，否则为 false。

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


将警告日志消息写入控制台。
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 警告日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


将警告日志消息写入控制台。
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 异常对象 | java.lang.Throwable | 与警告日志消息关联的异常。 |
|
|  | 消息 | java.lang.String | 警告日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


检查是否已启用警告级别的日志记录。


**Returns:**
布尔型 - 如果启用了警告级别则为 true，否则为 false。

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


将错误日志消息写入控制台。
错误日志消息提供有关应用程序流程中不可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 消息 | java.lang.String | 错误日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


将错误日志消息写入控制台。
错误日志消息提供有关应用程序流程中不可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 异常对象 | java.lang.Throwable | 与错误日志消息关联的异常。 |
|
|  | 消息 | java.lang.String | 错误日志消息。 |
|
|  | 参数 | java.lang.Object[] | 将在消息中被替换的参数。它们将按传递顺序替换 {} 占位符。 |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


检查是否已启用错误级别的日志记录。


**Returns:**
布尔型 - 如果启用了错误级别日志记录则为 true，否则为 false。

