---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "全局查看器日志记录器。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

全局查看器日志记录器。


该
ViewerLogger
类提供将消息记录到集成或用户定义的记录器的功能。
它作为 viewer 模块的全局记录器，可用于记录各种事件和消息。


示例用法：

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
类可以通过调用 [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-) 方法来配置使用自定义记录器实现。
默认情况下，它使用 viewer 模块提供的集成记录器。*

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
|  | [getLogger()](#getLogger--) | 获取将用于记录消息的记录器实例。 |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 设置将用于记录消息的记录器实例。 |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
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
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


检查是否已启用跟踪级别的日志记录。


**Returns:**
布尔型 - 如果启用了跟踪级别则为 true，否则为 false。

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
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
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


检查是否已启用调试级别的日志记录。


**Returns:**
布尔型 - 如果启用了调试级别则为 true，否则为 false。

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
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
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


检查是否已启用警告级别的日志记录。


**Returns:**
布尔型 - 如果启用了警告级别则为 true，否则为 false。

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
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
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


检查是否已启用错误级别的日志记录。


**Returns:**
布尔型 - 如果启用了错误级别日志记录则为 true，否则为 false。

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


获取将用于记录消息的记录器实例。
日志实例可用于记录不同级别的消息，如跟踪、调试、警告和错误。


**Returns:**
com.groupdocs.foundation.logging.ILogger - 日志实例。

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


设置将用于记录消息的记录器实例。
日志实例可用于记录不同级别的消息，如跟踪、调试、警告和错误。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 日志记录器 | com.groupdocs.foundation.logging.ILogger | 要设置的日志实例。 |
|

