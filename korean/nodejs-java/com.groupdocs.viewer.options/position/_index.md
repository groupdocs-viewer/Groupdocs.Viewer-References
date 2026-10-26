---
title: "Position"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "워터마크 위치를 정의합니다."
type: docs
weight: 43
url: /ko/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

워터마크 위치를 정의합니다.

Position 열거형은 GroupDocs.Viewer 구성 요소에서 워터마크의 다양한 위치를 나타냅니다. 렌더링 과정에서 문서나 이미지에 워터마크를 배치하기 위해 사용할 수 있는 미리 정의된 위치 집합을 제공합니다.

예시 사용법:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | 대각선 위치. |
| [TOP_LEFT](#TOP-LEFT) | 왼쪽 상단 위치. |
| [TOP_CENTER](#TOP-CENTER) | 상단 중앙 위치. |
| [TOP_RIGHT](#TOP-RIGHT) | 오른쪽 상단 위치. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | 왼쪽 하단 위치. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | 하단 중앙 위치. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | 오른쪽 하단 위치. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


대각선 위치. 이 위치는 대각선 정렬 또는 배치를 나타냅니다.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


왼쪽 상단 위치. 이 위치는 왼쪽 상단 모서리 정렬 또는 배치를 나타냅니다.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


상단 중앙 위치. 이 위치는 상단 중앙 정렬 또는 배치를 나타냅니다.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


오른쪽 상단 위치. 이 위치는 오른쪽 상단 모서리 정렬 또는 배치를 나타냅니다.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


왼쪽 하단 위치. 이 위치는 왼쪽 하단 모서리 정렬 또는 배치를 나타냅니다.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


하단 중앙 위치. 이 위치는 하단 중앙 정렬 또는 배치를 나타냅니다.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


오른쪽 하단 위치. 이 위치는 오른쪽 하단 모서리 정렬 또는 배치를 나타냅니다.

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
