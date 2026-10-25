---
title: "Watermark"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "텍스트 워터마크를 나타냅니다."
type: docs
weight: 37
url: /ko/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

텍스트 워터마크를 나타냅니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/add-text-watermark/)을 참조하세요.


Watermark 클래스는 GroupDocs.Viewer 구성 요소에서 텍스트 워터마크를 나타냅니다.
이 클래스는 문서의 렌더링된 출력에 워터마크를 정의하고 적용하는 데 사용됩니다.


사용 예시:

````

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
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | 새 인스턴스를 초기화합니다. |
Watermark
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 워터마크 텍스트를 반환합니다. |
|
|  | [getColor()](#getColor--) | 워터마크 색상을 반환합니다. |
|
|  | [getColorAsHex()](#getColorAsHex--) | 워터마크 색상을 16진수 형식으로 반환합니다. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 워터마크 색상을 설정합니다. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | 워터마크 색상을 설정합니다. |
|
|  | [getPosition()](#getPosition--) | 워터마크 위치를 반환합니다. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | 워터마크 위치를 설정합니다. |
|
|  | [getSize()](#getSize--) | 워터마크 크기를 반환합니다. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | 워터마크 크기를 설정합니다. |
|
|  | [getFontName()](#getFontName--) | 워터마크에 사용되는 글꼴 이름을 반환합니다. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | 워터마크에 사용되는 글꼴 이름을 설정합니다. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


새 인스턴스를 초기화합니다.
Watermark
클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 워터마크 텍스트입니다. |
|

### getText() {#getText--}
```
public final String getText()
```


워터마크 텍스트를 반환합니다.
이 메서드는 문서에 적용된 워터마크의 텍스트를 검색합니다.


**Returns:**
java.lang.String - 워터마크 텍스트.

### getColor() {#getColor--}
```
public final Color getColor()
```


워터마크 색상을 반환합니다.
이 메서드는 문서에 적용된 워터마크의 색상을 검색합니다.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - 워터마크 색상.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


워터마크 색상을 16진수 형식으로 반환합니다.
이 메서드는 문서에 적용된 워터마크의 색상을 검색합니다.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - 16진수 형식의 워터마크 색상.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


워터마크 색상을 설정합니다.
이 메서드는 문서에 적용된 워터마크의 색상을 설정합니다.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.awt.Color | 설정할 워터마크 색상입니다. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


워터마크 색상을 설정합니다.
이 메서드는 문서에 적용된 워터마크의 색상을 설정합니다.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | colorName | java.lang.String | 설정할 워터마크 색상입니다. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


워터마크 위치를 반환합니다.
이 메서드는 문서에 적용된 워터마크의 위치를 반환합니다.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


워터마크 위치를 설정합니다.
이 메서드는 문서에 적용된 워터마크의 위치를 설정합니다.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | 워터마크 위치입니다. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


워터마크 크기를 반환합니다.
이 메서드는 문서에 적용된 워터마크의 크기를 검색합니다.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


워터마크 크기를 설정합니다.
이 메서드는 문서에 적용될 워터마크의 크기를 설정합니다.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | 워터마크 크기입니다. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


워터마크에 사용되는 글꼴 이름을 반환합니다.


**Returns:**
java.lang.String - 워터마크에 사용되는 글꼴 이름.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


워터마크에 사용되는 글꼴 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 워터마크에 사용되는 글꼴 이름입니다. |
|

