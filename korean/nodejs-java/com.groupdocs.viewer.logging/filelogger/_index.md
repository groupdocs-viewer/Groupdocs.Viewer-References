---
title: "FileLogger"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "로그 메시지를 파일에 기록합니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

로그 메시지를 파일에 기록합니다.

FileLogger 클래스는 로그 메시지를 파일에 기록하는 기능을 제공합니다. ILogger 인터페이스를 구현하며 애플리케이션에서 다양한 이벤트와 메시지를 기록하는 데 사용할 수 있습니다. 로그 메시지는 지정된 파일에 기록됩니다.

예시 사용법:

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
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | 제공된 파일 이름으로 지정된 파일에 메시지를 기록하는 로거를 생성합니다. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | 지정된 로깅 레벨로 파일에 메시지를 기록하는 로거를 생성합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | 콘솔에 추적 메시지를 기록합니다. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 추적 로그 메시지를 기록합니다. |
| [isTraceEnabled()](#isTraceEnabled--) | 추적 레벨이 로깅에 사용 가능한지 확인합니다. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | 콘솔에 디버그 로그 메시지를 기록합니다. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 디버그 로그 메시지를 기록합니다. |
| [isDebugEnabled()](#isDebugEnabled--) | 디버그 레벨이 로깅에 사용 가능한지 확인합니다. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | 콘솔에 경고 로그 메시지를 기록합니다. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 경고 로그 메시지를 기록합니다. |
| [isWarningEnabled()](#isWarningEnabled--) | 경고 레벨이 로깅에 사용 가능한지 확인합니다. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | 콘솔에 오류 로그 메시지를 기록합니다. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | 콘솔에 오류 로그 메시지를 기록합니다. |
| [isErrorEnabled()](#isErrorEnabled--) | 오류 레벨 로깅이 사용 가능한지 확인합니다. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


제공된 파일 이름으로 지정된 파일에 메시지를 기록하는 로거를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 전체 파일 경로와 파일 이름입니다. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


지정된 로깅 레벨로 파일에 메시지를 기록하는 로거를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 전체 파일 경로와 파일 이름입니다. |
| isTraceEnabled | boolean | 추적 레벨 로깅이 활성화되어 있는지 지정합니다. |
| isDebugEnabled | boolean | 디버그 레벨 로깅이 활성화되어 있는지 지정합니다. |
| isWarningEnabled | boolean | 경고 레벨 로깅이 활성화되어 있는지 지정합니다. |
| isErrorEnabled | boolean | 오류 레벨 로깅이 활성화되어 있는지 지정합니다. |

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


콘솔에 추적 메시지를 기록합니다. 추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 추적 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 인수는 전달 순서대로 \{\} 자리표시자를 교체합니다. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


콘솔에 트레이스 로그 메시지를 기록합니다. 트레이스 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| throwable | java.lang.Throwable | 트레이스 로그 메시지와 연결된 예외입니다. |
| 메시지 | java.lang.String | 트레이스 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


추적 레벨이 로깅에 사용 가능한지 확인합니다.

**Returns:**
boolean -  true  트레이스 레벨이 활성화된 경우,  false  그렇지 않은 경우.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


콘솔에 디버그 로그 메시지를 기록합니다. 디버그 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 디버그 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


콘솔에 디버그 로그 메시지를 기록합니다. 디버그 로그 메시지는 애플리케이션 흐름의 다양한 프로세스에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| throwable | java.lang.Throwable | 디버그 로그 메시지와 연결된 예외입니다. |
| 메시지 | java.lang.String | 디버그 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


디버그 레벨이 로깅에 사용 가능한지 확인합니다.

**Returns:**
boolean -  true  디버그 레벨이 활성화된 경우,  false  그렇지 않은 경우.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


콘솔에 경고 로그 메시지를 기록합니다. 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 경고 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


콘솔에 경고 로그 메시지를 기록합니다. 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| throwable | java.lang.Throwable | 경고 로그 메시지와 연결된 예외입니다. |
| 메시지 | java.lang.String | 경고 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


경고 레벨이 로깅에 사용 가능한지 확인합니다.

**Returns:**
boolean -  true  경고 레벨이 활성화된 경우,  false  그렇지 않은 경우.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


콘솔에 오류 로그 메시지를 기록합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


콘솔에 오류 로그 메시지를 기록합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구 불가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| throwable | java.lang.Throwable | 오류 로그 메시지와 연결된 예외입니다. |
| 메시지 | java.lang.String | 오류 로그 메시지. |
| 인수 | java.lang.Object[] | 메시지에서 교체될 인수입니다. 전달된 순서대로 \\{\\} 자리표시자를 교체합니다. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


오류 레벨 로깅이 사용 가능한지 확인합니다.

**Returns:**
boolean -  true  오류 레벨 로깅이 활성화된 경우,  false  그렇지 않은 경우.
