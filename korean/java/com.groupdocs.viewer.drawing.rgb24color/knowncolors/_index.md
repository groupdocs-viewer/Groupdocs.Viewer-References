---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java API Reference"
description: 
type: docs
weight: 10
url: /ko/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | 문자열 이름으로 색상을 찾으려고 시도합니다. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | RGB 값으로 색상 이름을 찾으려고 시도합니다. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


문자열 이름으로 색상을 찾으려고 시도합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | keyword | java.lang.String | 색상 이름입니다. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | 찾은 색상의 결과 컨테이너이며, 실패 시 CssLevel1.Black을 반환합니다. |
|

**Returns:**
boolean - 이름으로 색상을 성공적으로 찾은 경우 true, 그렇지 않으면 false.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


RGB 값으로 색상 이름을 찾으려고 시도합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | 색상 인스턴스입니다. |
|
|  | 이름 | java.lang.String[] | 찾은 색상 이름의 결과 컨테이너이며, 실패 시 null을 반환합니다. |
|

**Returns:**
boolean - 주어진 색상에 대해 이름을 성공적으로 찾은 경우 true, 그렇지 않으면 false.

