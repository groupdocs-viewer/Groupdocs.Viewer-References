---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "아카이브 파일을 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

아카이브 파일을 렌더링하기 위한 옵션을 제공합니다.


그
ArchiveOptions
클래스는 뷰어 모듈에서 아카이브 파일 렌더링을 구성하는 데 사용할 수 있는 옵션 집합을 나타냅니다.
페이지당 항목 수 등 렌더링 프로세스의 다양한 측면을 사용자 정의할 수 있습니다.


사용 예시:

````

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
````


***Note:** The 
ArchiveOptions
클래스는 아카이브 파일 렌더링을 위한 다양한 사용자 정의 옵션을 제공합니다.
특정 요구 사항에 따라 이러한 옵션을 구성하여 원하는 출력 결과를 얻을 수 있습니다.*

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ArchiveOptions()](#ArchiveOptions--) | 기본 설정으로 ArchiveOptions 클래스의 새 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFolder()](#getFolder--) | 렌더링에 사용할 아카이브 내부 폴더를 가져옵니다. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | 렌더링에 사용할 아카이브 내부 폴더를 설정합니다. |
|
|  | [getFileName()](#getFileName--) | 헤더에 표시될 파일 이름을 가져옵니다. |
|
|  | [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | 헤더에 표시될 파일 이름을 설정합니다. |
|
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


기본 설정으로 ArchiveOptions 클래스의 새 인스턴스를 생성합니다.


### getFolder() {#getFolder--}
```
public final String getFolder()
```


렌더링에 사용할 아카이브 내부 폴더를 가져옵니다.


기본적으로 GroupDocs.Viewer는 아카이브에 포함된 모든 폴더의 항목을 렌더링합니다. 특정 폴더의 항목을 렌더링하려면 이 속성을 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder)를 참조하십시오.


**Returns:**
java.lang.String - 렌더링할 폴더.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


렌더링에 사용할 아카이브 내부 폴더를 설정합니다.


기본적으로 GroupDocs.Viewer는 아카이브에 포함된 모든 폴더의 항목을 렌더링합니다. 특정 폴더의 항목을 렌더링하려면 이 속성을 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 렌더링할 폴더. |
|

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


헤더에 표시될 파일 이름을 가져옵니다.


기본적으로 GroupDocs.Viewer는 각 페이지의 헤더에 아카이브 파일 이름을 표시합니다. 이 이름을 변경하거나 숨기려면 이 속성을 설정하십시오.
자세한 정보와 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name)을 참조하십시오.


**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.

### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


헤더에 표시될 파일 이름을 설정합니다.


기본적으로 GroupDocs.Viewer는 각 페이지의 헤더에 아카이브 파일 이름을 표시합니다. 이 이름을 변경하거나 숨기려면 이 속성을 설정하십시오.
자세한 정보와 코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileName | [FileName](../../com.groupdocs.viewer.options/filename) | 표시될 파일 이름입니다. |
|

