---
title: "Size"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "워터마크 크기를 포함합니다."
type: docs
weight: 30
url: /ko/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

워터마크 크기를 포함합니다.

Size 클래스는 GroupDocs.Viewer 구성 요소에서 워터마크의 크기를 나타냅니다. 너비와 높이와 같은 워터마크의 차원을 지정하는 옵션을 제공합니다.

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
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Size 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | 페이지에 맞는 워터마크 텍스트의 최대 크기를 나타냅니다. |
| [HALF_SIZE](#HALF-SIZE) | 페이지에 맞는 워터마크 텍스트 최대 크기의 절반을 나타냅니다. |
| [ONE_THIRD](#ONE-THIRD) | 페이지에 맞는 워터마크 텍스트 최대 크기의 1/3을 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | 페이지 너비에 대한 비율로 워터마크 텍스트 크기를 백분율로 반환합니다. |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Size 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| relativeSize | byte | 페이지 크기에 대한 비율로 백분율 크기입니다. |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


페이지에 맞는 워터마크 텍스트의 최대 크기를 나타냅니다.

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


페이지에 맞는 워터마크 텍스트 최대 크기의 절반을 나타냅니다.

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


페이지에 맞는 워터마크 텍스트 최대 크기의 1/3을 나타냅니다.

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


페이지 너비에 대한 비율로 워터마크 텍스트 크기를 백분율로 반환합니다.

**Returns:**
byte - 워터마크 텍스트 크기의 백분율입니다.
