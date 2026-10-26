---
title: "TextOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "텍스트 파일을 페이지로 분할하는 옵션입니다."
type: docs
weight: 32
url: /ko/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

텍스트 파일을 페이지로 분할하는 옵션입니다.

TextOptions 클래스는 GroupDocs.Viewer 구성 요소에서 텍스트 파일을 페이지로 분할하기 위한 옵션을 제공합니다. 이를 통해 텍스트 파일이 렌더링 및 보기 목적을 위해 개별 페이지로 어떻게 나뉘는지 제어할 수 있습니다.

예시 사용법:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextOptions()](#TextOptions--) | TextOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | 페이지에서 행당 최대 문자 수를 가져옵니다. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | 페이지에서 행당 최대 문자 수를 설정합니다. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | 페이지당 최대 행 수를 가져옵니다. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | 페이지당 최대 행 수를 설정합니다. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


TextOptions 클래스의 새 인스턴스를 초기화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


페이지에서 행당 최대 문자 수를 가져옵니다.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - 페이지에서 행당 최대 문자 수.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


페이지에서 행당 최대 문자 수를 설정합니다.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxCharsPerRow | int | 페이지에서 행당 최대 문자 수. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


페이지당 최대 행 수를 가져옵니다.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - 최대 행 수.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


페이지당 최대 행 수를 설정합니다.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxRowsPerPage | int | 최대 행 수. |

