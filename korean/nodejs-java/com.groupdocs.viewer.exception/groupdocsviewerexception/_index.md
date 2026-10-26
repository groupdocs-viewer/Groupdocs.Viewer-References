---
title: "GroupDocsViewerException"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "이 예외는 문서 처리 중에 발생할 수 있는 일반적인 오류를 나타냅니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.viewer.exception/groupdocsviewerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, com.groupdocs.foundation.exception.GroupDocsException
```
public class GroupDocsViewerException extends GroupDocsException
```

이 예외는 문서 처리 중 발생할 수 있는 일반적인 오류를 나타냅니다. 이는 오류나 실패를 나타내는 포괄적인 예외이지만, 오류의 성격에 대한 구체적인 세부 정보를 제공하지 않습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GroupDocsViewerException(String message)](#GroupDocsViewerException-java.lang.String-) | GroupDocsViewerException 클래스의 새 인스턴스를 지정된 오류 메시지와 함께 초기화합니다. |
| [GroupDocsViewerException(Throwable cause)](#GroupDocsViewerException-java.lang.Throwable-) | GroupDocsViewerException 클래스의 새 인스턴스를 예외의 원인과 함께 초기화합니다. |
| [GroupDocsViewerException(String message, Throwable throwable)](#GroupDocsViewerException-java.lang.String-java.lang.Throwable-) | GroupDocsViewerException 클래스의 새 인스턴스를 지정된 오류 메시지와 함께 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [toString()](#toString--) |  |
### GroupDocsViewerException(String message) {#GroupDocsViewerException-java.lang.String-}
```
public GroupDocsViewerException(String message)
```


GroupDocsViewerException 클래스의 새 인스턴스를 지정된 오류 메시지와 함께 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류를 설명하는 메시지. |

### GroupDocsViewerException(Throwable cause) {#GroupDocsViewerException-java.lang.Throwable-}
```
public GroupDocsViewerException(Throwable cause)
```


GroupDocsViewerException 클래스의 새 인스턴스를 예외의 원인과 함께 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 원인 | java.lang.Throwable | 예외의 원인입니다. |

### GroupDocsViewerException(String message, Throwable throwable) {#GroupDocsViewerException-java.lang.String-java.lang.Throwable-}
```
public GroupDocsViewerException(String message, Throwable throwable)
```


GroupDocsViewerException 클래스의 새 인스턴스를 지정된 오류 메시지와 함께 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류를 설명하는 메시지. |
| throwable | java.lang.Throwable | 예외를 발생시킨 throwable입니다. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
