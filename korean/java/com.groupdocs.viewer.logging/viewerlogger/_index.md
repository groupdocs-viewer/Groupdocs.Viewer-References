---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "전역 뷰어 로거."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

전역 뷰어 로거.


그
ViewerLogger
클래스는 통합되거나 사용자 정의 로거에 메시지를 기록하는 기능을 제공합니다.
이것은 뷰어 모듈의 전역 로거 역할을 하며 다양한 이벤트와 메시지를 기록하는 데 사용할 수 있습니다.


사용 예시:

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
클래스는 [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-) 메서드를 호출하여 사용자 정의 로거 구현을 사용하도록 구성할 수 있습니다.
기본적으로, 뷰어 모듈에서 제공하는 통합 로거를 사용합니다.*

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 콘솔에 추적 메시지를 씁니다. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 추적 로그 메시지를 씁니다. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | 추적 레벨이 로깅에 사용 가능한지 확인합니다. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 콘솔에 디버그 로그 메시지를 씁니다. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 디버그 로그 메시지를 씁니다. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | 디버그 레벨이 로깅에 사용 가능한지 확인합니다. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 콘솔에 경고 로그 메시지를 씁니다. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 경고 로그 메시지를 씁니다. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | 경고 레벨이 로깅에 사용 가능한지 확인합니다. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 콘솔에 오류 로그 메시지를 씁니다. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 오류 로그 메시지를 씁니다. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | 오류 수준 로깅이 사용 가능한지 확인합니다. |
|
|  | [getLogger()](#getLogger--) | 메시지 로깅에 사용할 로거 인스턴스를 가져옵니다. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | 메시지 로깅에 사용할 로거 인스턴스를 설정합니다. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


콘솔에 추적 메시지를 씁니다.
추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 추적 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달 순서대로 {} 자리표시자를 교체합니다. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


콘솔에 추적 로그 메시지를 씁니다.
Trace 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | trace 로그 메시지와 연결된 예외입니다. |
|
|  | 메시지 | java.lang.String | trace 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


추적 레벨이 로깅에 사용 가능한지 확인합니다.


**Returns:**
boolean - trace 레벨이 활성화된 경우 true, 그렇지 않으면 false.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


콘솔에 디버그 로그 메시지를 씁니다.
Debug 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | debug 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


콘솔에 디버그 로그 메시지를 씁니다.
Debug 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | debug 로그 메시지와 연결된 예외입니다. |
|
|  | 메시지 | java.lang.String | debug 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


디버그 레벨이 로깅에 사용 가능한지 확인합니다.


**Returns:**
boolean - debug 레벨이 활성화된 경우 true, 그렇지 않으면 false.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


콘솔에 경고 로그 메시지를 씁니다.
Warning 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | warning 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


콘솔에 경고 로그 메시지를 씁니다.
Warning 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | warning 로그 메시지와 연결된 예외입니다. |
|
|  | 메시지 | java.lang.String | warning 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


경고 레벨이 로깅에 사용 가능한지 확인합니다.


**Returns:**
boolean - warning 레벨이 활성화된 경우 true, 그렇지 않으면 false.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


콘솔에 오류 로그 메시지를 씁니다.
Error 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | error 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


콘솔에 오류 로그 메시지를 씁니다.
Error 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | error 로그 메시지와 연결된 예외입니다. |
|
|  | 메시지 | java.lang.String | error 로그 메시지. |
|
|  | 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달되는 순서대로 {} 자리표시자를 교체합니다. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


오류 수준 로깅이 사용 가능한지 확인합니다.


**Returns:**
boolean - error 레벨 로깅이 활성화된 경우 true, 그렇지 않으면 false.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


메시지 로깅에 사용할 로거 인스턴스를 가져옵니다.
logger 인스턴스를 사용하여 trace, debug, warning, error와 같은 다양한 레벨의 메시지를 기록할 수 있습니다.


**Returns:**
com.groupdocs.foundation.logging.ILogger - logger 인스턴스.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


메시지 로깅에 사용할 로거 인스턴스를 설정합니다.
logger 인스턴스를 사용하여 trace, debug, warning, error와 같은 다양한 레벨의 메시지를 기록할 수 있습니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | 설정할 logger 인스턴스. |
|

