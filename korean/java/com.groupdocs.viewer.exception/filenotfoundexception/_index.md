---
title: "FileNotFoundException"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "파일이나 디렉터리를 찾을 수 없을 때 이 예외가 발생합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.exception/filenotfoundexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException, [com.groupdocs.viewer.exception.GroupDocsViewerException](../../com.groupdocs.viewer.exception/groupdocsviewerexception)
```
public class FileNotFoundException extends GroupDocsViewerException
```

파일이나 디렉터리를 찾을 수 없을 때 이 예외가 발생합니다. 지정된 파일이나 디렉터리가 존재하지 않거나 접근할 수 없음을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileNotFoundException(String message)](#FileNotFoundException-java.lang.String-) | 지정된 메시지를 사용하여 FileNotFoundException 클래스의 인스턴스를 생성합니다. |
|
|  | [FileNotFoundException(Path path)](#FileNotFoundException-java.nio.file.Path-) | 지정된 파일 경로를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [FileNotFoundException(String messageTemplate, Object[] params)](#FileNotFoundException-java.lang.String-java.lang.Object...-) | 지정된 오류 메시지를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 생성합니다. |
|
|  | [FileNotFoundException(Throwable cause)](#FileNotFoundException-java.lang.Throwable-) | FileNotFoundException 클래스의 새 인스턴스를 인스턴스화합니다. |
|
|  | [FileNotFoundException(String message, Throwable throwable)](#FileNotFoundException-java.lang.String-java.lang.Throwable-) | 지정된 오류 메시지를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 초기화합니다. |
|
### FileNotFoundException(String message) {#FileNotFoundException-java.lang.String-}
```
public FileNotFoundException(String message)
```


지정된 메시지를 사용하여 FileNotFoundException 클래스의 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 오류를 설명하는 메시지. |
|

### FileNotFoundException(Path path) {#FileNotFoundException-java.nio.file.Path-}
```
public FileNotFoundException(Path path)
```


지정된 파일 경로를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 경로 | java.nio.file.Path | 존재하지 않는 파일의 경로. |
|

### FileNotFoundException(String messageTemplate, Object[] params) {#FileNotFoundException-java.lang.String-java.lang.Object...-}
```
public FileNotFoundException(String messageTemplate, Object[] params)
```


지정된 오류 메시지를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | messageTemplate | java.lang.String | 오류를 설명하는 메시지. |
|
|  | 매개변수 | java.lang.Object[] | 오류 메시지에 설정될 매개변수들. |
|

### FileNotFoundException(Throwable cause) {#FileNotFoundException-java.lang.Throwable-}
```
public FileNotFoundException(Throwable cause)
```


FileNotFoundException 클래스의 새 인스턴스를 인스턴스화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 원인 | java.lang.Throwable | 예외의 원인. |
|

### FileNotFoundException(String message, Throwable throwable) {#FileNotFoundException-java.lang.String-java.lang.Throwable-}
```
public FileNotFoundException(String message, Throwable throwable)
```


지정된 오류 메시지를 사용하여 FileNotFoundException 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 오류를 설명하는 메시지. |
|
|  | throwable | java.lang.Throwable | 예외를 발생시킨 throwable. |
|

