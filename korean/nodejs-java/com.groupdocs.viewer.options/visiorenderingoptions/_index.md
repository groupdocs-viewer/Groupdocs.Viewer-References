---
title: "VisioRenderingOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Visio 문서를 렌더링하기 위한 옵션을 포함합니다."
type: docs
weight: 36
url: /ko/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio 문서를 렌더링하기 위한 옵션을 포함합니다.

VisioRenderingOptions 클래스는 GroupDocs.Viewer 구성 요소에서 Visio 파일을 처리하고 렌더링하기 위한 옵션을 제공합니다. 이 클래스는 Visio 문서의 렌더링 프로세스와 출력 형식을 제어하는 데 사용할 수 있는 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 [문서][]를 참조하십시오.

예시 사용법:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | VisioRenderingOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | 다이어그램을 제외하고 Visio 도형만 렌더링합니다. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | 다이어그램을 제외하고 Visio 도형만 렌더링하도록 플래그를 설정합니다. |
| [getFigureWidth()](#getFigureWidth--) | 도형의 너비를 가져옵니다. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | 도형의 너비를 설정합니다. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


VisioRenderingOptions 클래스의 새 인스턴스를 초기화합니다.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


다이어그램을 제외하고 Visio 도형만 렌더링합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  경우에만 Visio 도형을 렌더링하고,  false  그 외의 경우.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


다이어그램을 제외하고 Visio 도형만 렌더링하도록 플래그를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  경우에만 Visio 도형을 렌더링하고,  false  경우에는 다이어그램을 포함합니다. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


도형의 너비를 가져옵니다. 높이는 자동으로 계산됩니다.

**Returns:**
int - 도형의 너비.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


도형의 너비를 설정합니다. 높이는 자동으로 계산됩니다.

***Note:** Default value is 100.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| figureWidth | int | 도형의 너비. |

