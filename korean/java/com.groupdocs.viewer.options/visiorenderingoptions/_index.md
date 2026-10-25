---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Visio 문서를 렌더링하기 위한 옵션을 포함합니다."
type: docs
weight: 36
url: /ko/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio 문서를 렌더링하기 위한 옵션을 포함합니다.


VisioRenderingOptions 클래스는 Visio 파일을 처리하고 렌더링하기 위한 옵션을 제공합니다.
GroupDocs.Viewer 구성 요소에서. 사용될 수 있는 설정 및 매개변수를 캡슐화합니다.
Visio 문서의 렌더링 프로세스 및 출력 형식을 제어합니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/render-visio-documents/)를 참조하십시오.


사용 예시:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | 새 인스턴스를 초기화합니다. |
VisioRenderingOptions
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | 다이어그램을 제외하고 Visio 도형만 렌더링합니다. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | 다이어그램을 제외하고 Visio 도형만 렌더링하도록 플래그를 설정합니다. |
|
|  | [getFigureWidth()](#getFigureWidth--) | 도형의 너비를 가져옵니다. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | 도형의 너비를 설정합니다. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


새 인스턴스를 초기화합니다.
VisioRenderingOptions
클래스.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


다이어그램을 제외하고 Visio 도형만 렌더링합니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)를 참조하십시오.


**Returns:**
boolean -  true  경우 Visio 도형만 렌더링되고,  false  경우 그렇지 않습니다.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


다이어그램을 제외하고 Visio 도형만 렌더링하도록 플래그를 설정합니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  - Visio 도형만 렌더링,  false  - 다이어그램을 포함합니다. |
|

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
|  | figureWidth | int | 도형의 너비. |
|

