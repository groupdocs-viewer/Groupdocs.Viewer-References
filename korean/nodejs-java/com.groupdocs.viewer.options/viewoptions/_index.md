---
title: "ViewOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "렌더링 옵션을 포함합니다."
type: docs
weight: 35
url: /ko/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

렌더링 옵션을 포함합니다.

ViewOptions 클래스는 BaseViewOptions 클래스를 상속하며 GroupDocs.Viewer 구성 요소에서 렌더링 옵션의 기본 클래스로 사용됩니다. 이는 다양한 유형의 문서를 다양한 형식으로 렌더링하는 데 사용할 수 있는 공통 설정 및 매개변수를 캡슐화합니다.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWatermark()](#getWatermark--) | 각 페이지에 적용된 텍스트 워터마크를 가져옵니다. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | 각 페이지에 적용될 텍스트 워터마크를 설정합니다. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | 지정된 페이지에 시계 방향 회전을 적용합니다. |
| [getPageRotations()](#getPageRotations--) | 페이지 회전 정보를 가져옵니다. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | 인스턴스를 생성하여 비어 있는지 확인하는 것을 방지하기 위해 |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


각 페이지에 적용된 텍스트 워터마크를 가져옵니다.

두 개의 \#setWatermark(Watermark).setWatermark(Watermark)와 \#getPageRotations().getPageRotations()가 모두 지정된 경우, 워터마크가 회전된 페이지에 적용됩니다. 자세한 내용은 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


각 페이지에 적용될 텍스트 워터마크를 설정합니다.

두 개의  ViewOptions.Watermark 와 \#getPageRotations().getPageRotations()가 모두 지정된 경우, 워터마크가 회전된 페이지에 적용됩니다. 자세한 내용은 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | 설정할 텍스트 워터마크. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


지정된 페이지에 시계 방향 회전을 적용합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | int | 페이지 번호는 0보다 엄격히 커야 합니다. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | 회전 값. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


페이지 회전 정보를 가져옵니다.

두 [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-)와 getPageRotations()가 모두 지정된 경우, 워터마크가 회전된 페이지에 적용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - 페이지 번호를 키로 하고 해당 회전을 값으로 포함하는 맵.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


인스턴스를 생성하여 비어 있는지 확인하는 것을 방지하기 위해

**Returns:**
boolean
