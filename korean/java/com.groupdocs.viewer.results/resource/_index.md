---
title: "Resource"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "글꼴, 스타일, 이미지 또는 그래픽과 같은 HTML 리소스를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

폰트, 스타일, 이미지 또는 그래픽과 같은 HTML 리소스를 나타냅니다.


Resource 클래스는 GroupDocs.Viewer 구성 요소에서 HTML 렌더링에 사용되는 리소스를 나타냅니다.
포함된 글꼴, 스타일, 이미지 또는 그래픽과 같은 다양한 유형의 리소스를 나타낼 수 있습니다
또는 렌더링 과정에서 생성된 HTML 출력에 참조됩니다.


사용 예시:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | 새 인스턴스를 생성합니다 |
Resource
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileName()](#getFileName--) | 리소스의 파일 이름을 반환합니다. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | 리소스의 파일 이름을 설정합니다. |
|
|  | [isNested()](#isNested--) | 리소스가 다른 리소스 내부에 존재하는지 여부를 반환합니다. 예: CSS 또는 SVG 리소스에 포함된 글꼴 리소스. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | 리소스가 다른 리소스 내부에 존재하는지 여부를 설정합니다. |
|
|  | [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


새 인스턴스를 생성합니다
Resource
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileName | java.lang.String | 리소스 파일 이름. |
|
|  | 중첩된 | boolean | 리소스가 다른 리소스 내부에 존재하는지 여부를 나타냅니다. 예: CSS 또는 SVG 리소스에 포함된 글꼴 리소스. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


리소스의 파일 이름을 반환합니다.


**Returns:**
java.lang.String - 리소스의 파일 이름.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


리소스의 파일 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileName | java.lang.String | 리소스의 새 파일 이름. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


리소스가 다른 리소스 내부에 존재하는지 여부를 반환합니다. 예: CSS 또는 SVG 리소스에 포함된 글꼴 리소스.


**Returns:**
boolean - 리소스가 다른 리소스 내부에 존재하는지 여부.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


리소스가 다른 리소스 내부에 존재하는지 여부를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 중첩된 | boolean | 리소스를 중첩으로 설정해야 하는지 여부. |
|

### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.


**Returns:**
java.lang.String - 현재 객체의 문자열 표현.

