---
title: "FileName"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "아카이브 내 파일 이름을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

아카이브 내 파일 이름을 나타냅니다.


FileName 클래스는 경로나 디렉터리 정보 없이 파일 이름을 캡슐화합니다.
파일 이름에 대한 정보를 조작하고 검색하는 메서드를 제공합니다.


사용 예시:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | 새 인스턴스를 초기화합니다. |
FileName
클래스.
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [EMPTY](#EMPTY) | 빈 파일 이름을 나타냅니다. |
|
|  | [SOURCE](#SOURCE) | 소스 파일의 이름을 나타냅니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | 현재 객체의 문자열 표현을 반환합니다. |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


새 인스턴스를 초기화합니다.
FileName
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileName | java.lang.String | 파일의 이름입니다. |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


빈 파일 이름을 나타냅니다.


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


소스 파일의 이름을 나타냅니다.


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


현재 객체의 문자열 표현을 반환합니다.


**Returns:**
java.lang.String - 현재 객체의 문자열 표현입니다.

