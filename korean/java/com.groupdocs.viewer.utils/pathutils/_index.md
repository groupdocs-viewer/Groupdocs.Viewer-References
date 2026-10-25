---
title: "PathUtils"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PathUtils 클래스는 파일 경로 작업을 위한 유틸리티 메서드를 제공합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils 클래스는 파일 경로 작업을 위한 유틸리티 메서드를 제공합니다.


PathUtils 클래스는 다양한 작업을 수행할 수 있는 정적 메서드를 포함합니다
GroupDocs.Viewer 구성 요소의 파일 경로에 대해


사용 예시:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | 구분자를 사용하여 경로 부분을 결합합니다. |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | 파일 이름을 가져옵니다. |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


구분자를 사용하여 경로 부분을 결합합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 매개변수 | java.lang.String[] | 경로 부분 |
|

**Returns:**
java.lang.String - 결과 경로

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


파일 이름을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 경로 | java.lang.String | 경로 |
|

**Returns:**
java.lang.String - 파일 이름

