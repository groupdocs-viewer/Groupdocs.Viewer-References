---
title: "타일"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "그리기 영역을 나타냅니다."
type: docs
weight: 33
url: /ko/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

그리기 영역을 나타냅니다.


Tile 클래스는 GroupDocs.Viewer 구성 요소에서 그리기 영역을 나타냅니다.
문서 내에서 별도로 렌더링하거나 처리해야 하는 특정 영역을 정의하는 데 사용됩니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


사용 예시:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | 새 인스턴스를 초기화합니다. |
타일
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | 타일이 시작되는 그림의 가장 왼쪽 아래 점의 X 좌표를 가져옵니다. |
|
|  | [getStartPointY()](#getStartPointY--) | 타일이 시작되는 도면의 가장 왼쪽 아래 점의 Y 좌표를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 타일의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 타일의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [getEndPointX()](#getEndPointX--) | 타일이 끝나는 도면의 가장 오른쪽 위 점의 X 좌표를 반환합니다. |
|
|  | [getEndPointY()](#getEndPointY--) | 타일이 끝나는 도면의 가장 오른쪽 위 점의 Y 좌표를 반환합니다. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


새 인스턴스를 초기화합니다.
타일
클래스.


이 생성자는 지정된 시작점, 너비 및 높이를 사용하여 새로운 타일 객체를 생성합니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | startPointX | int | 타일이 시작되는 도면의 가장 왼쪽 아래 점의 X 좌표. |
|
|  | startPointY | int | 타일이 시작되는 도면의 가장 왼쪽 아래 점의 Y 좌표. |
|
|  | width | int | 타일의 너비(픽셀). |
|
|  | height | int | 타일의 높이(픽셀). |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


타일이 시작되는 그림의 가장 왼쪽 아래 점의 X 좌표를 가져옵니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


**Returns:**
int - 가장 왼쪽 아래 점의 X 좌표.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


타일이 시작되는 도면의 가장 왼쪽 아래 점의 Y 좌표를 가져옵니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


**Returns:**
int - 가장 왼쪽 아래 점의 Y 좌표.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


타일의 너비를 픽셀 단위로 가져옵니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


**Returns:**
int - 타일의 너비.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


타일의 높이를 픽셀 단위로 가져옵니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)을 참조하세요.


**Returns:**
int - 타일의 높이.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


타일이 끝나는 도면의 가장 오른쪽 위 점의 X 좌표를 반환합니다.


**Returns:**
int - 가장 오른쪽 위 점의 X 좌표.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


타일이 끝나는 도면의 가장 오른쪽 위 점의 Y 좌표를 반환합니다.


**Returns:**
int - 가장 오른쪽 위 점의 Y 좌표.

