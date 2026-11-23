---
title: "ViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "렌더링 옵션을 포함합니다."
type: docs
weight: 35
url: /ko/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

렌더링 옵션을 포함합니다.


ViewOptions 클래스는 BaseViewOptions 클래스를 확장하며 렌더링 옵션을 위한 기본 클래스 역할을 합니다.
GroupDocs.Viewer 구성 요소에서. 공통 설정 및 매개변수를 캡슐화하여 사용할 수 있습니다.
다양한 유형의 문서를 다양한 형식으로 렌더링하기 위해.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | 각 페이지에 적용된 텍스트 워터마크를 가져옵니다. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | 각 페이지에 적용될 텍스트 워터마크를 설정합니다. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | 지정된 페이지에 시계 방향 회전을 적용합니다. |
|
|  | [getPageRotations()](#getPageRotations--) | 페이지 회전을 가져옵니다. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | 인스턴스를 생성하여 비어 있는지 확인하는 것을 방지하기 위해 |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


각 페이지에 적용된 텍스트 워터마크를 가져옵니다.


두 경우 모두 #setWatermark(Watermark).setWatermark(Watermark)와 #getPageRotations().getPageRotations()가 지정된 경우,
워터마크가 회전된 페이지에 적용됩니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/)을 참조하십시오.


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


각 페이지에 적용될 텍스트 워터마크를 설정합니다.


두 경우 모두
ViewOptions.Watermark
그리고 #getPageRotations().getPageRotations()가 지정된 경우,
워터마크가 회전된 페이지에 적용됩니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/add-text-watermark/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | 설정될 텍스트 워터마크. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


지정된 페이지에 시계 방향 회전을 적용합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 페이지 번호는 0보다 크게 설정해야 합니다. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | 회전 값. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


페이지 회전을 가져옵니다.


두 경우 모두 [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-)와
getPageRotations()
지정됩니다,
워터마크가 회전된 페이지에 적용됩니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/)을 참조하십시오.


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - 페이지 번호를 키로, 해당 회전을 값으로 포함하는 맵입니다.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


인스턴스를 생성하여 비어 있는지 확인하는 것을 방지하기 위해


**Returns:**
boolean
