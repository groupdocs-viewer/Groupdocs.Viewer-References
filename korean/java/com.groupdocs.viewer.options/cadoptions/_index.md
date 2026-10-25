---
title: "CadOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CAD 도면을 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD 도면을 렌더링하기 위한 옵션을 제공합니다.


CadOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다
GroupDocs.Viewer 구성 요소에서 CAD 도면 렌더링을 제어합니다.


자세한 정보와 코드 예제는 [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) 및 [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/)를 참조하십시오.


사용 예시:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | 플로터와 연결된 PC3(플로터 구성) 파일을 검색합니다. |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | 플로터와 연결된 PC3(플로터 구성) 파일을 설정합니다. |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | 새 인스턴스를 초기화합니다. |
CadOptions
스케일 팩터별 렌더링을 위한 클래스.
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | 새 인스턴스를 초기화합니다. |
CadOptions
너비별 렌더링을 위한 클래스.
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | 새 인스턴스를 초기화합니다. |
CadOptions
높이별 렌더링을 위한 클래스.
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | 새 인스턴스를 초기화합니다. |
CadOptions
너비와 높이별 렌더링을 위한 클래스.
|
|  | [getScaleFactor()](#getScaleFactor--) | 렌더링을 위한 스케일 팩터를 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 출력 결과의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [getHeight()](#getHeight--) | 출력 결과의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 이미지의 배경 색상을 가져옵니다. |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | 이미지의 배경 색상을 가져옵니다. |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | 이미지의 배경 색상을 설정합니다. |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | 이미지의 배경 색상을 설정합니다. |
|
|  | [getTiles()](#getTiles--) | 렌더링할 그리기 영역을 가져옵니다. |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | 렌더링할 그리기 영역을 설정합니다. |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | CAD 문서의 레이아웃을 렌더링할지 여부를 나타냅니다. |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | CAD 문서의 레이아웃을 렌더링할지 여부를 설정합니다. |
|
|  | [getLayoutName()](#getLayoutName--) | 렌더링할 특정 레이아웃의 이름을 가져옵니다. |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | 렌더링할 특정 레이아웃의 이름을 설정합니다. |
|
|  | [getLayers()](#getLayers--) | 렌더링할 CAD 도면 레이어를 가져옵니다. |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | 렌더링할 CAD 도면 레이어를 가져옵니다. |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | 이 플래그를 true로 설정하면 CAD 제품군 내 모든 형식에 대해 특수한 성능 중심 변환 모드가 활성화됩니다. |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | 이 플래그를 true로 설정하면 CAD 제품군 내 모든 형식에 대해 특수한 성능 중심 변환 모드가 활성화됩니다. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | 이 CadOptions 객체가 다른 객체와 같은지 확인합니다. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


플로터와 연결된 PC3(플로터 구성) 파일을 검색합니다.


**Returns:**
java.lang.String - PC3 파일 경로.

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


플로터와 연결된 PC3(플로터 구성) 파일을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pc3File | java.lang.String | PC3 파일 경로. |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


새 인스턴스를 초기화합니다.
CadOptions
스케일 팩터별 렌더링을 위한 클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | scaleFactor | double | 렌더링을 위한 스케일 팩터입니다. 1보다 큰 값은 출력 결과를 확대하고, 0과 1 사이의 값은 출력 결과를 축소합니다. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


새 인스턴스를 초기화합니다.
CadOptions
너비별 렌더링을 위한 클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | width | int | 출력 결과의 너비를 픽셀 단위로 나타냅니다. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


새 인스턴스를 초기화합니다.
CadOptions
높이별 렌더링을 위한 클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | height | int | 출력 결과의 높이를 픽셀 단위로 나타냅니다. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


새 인스턴스를 초기화합니다.
CadOptions
너비와 높이별 렌더링을 위한 클래스.


코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | width | int | 출력 결과의 너비를 픽셀 단위로 나타냅니다. |
|
|  | height | int | 출력 결과의 높이를 픽셀 단위로 나타냅니다. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


렌더링을 위한 스케일 팩터를 가져옵니다.
1보다 큰 값은 출력 결과를 확대하고, 0과 1 사이의 값은 출력 결과를 축소합니다.


**Returns:**
double - 렌더링을 위한 스케일 팩터.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


출력 결과의 너비를 픽셀 단위로 가져옵니다.


**Returns:**
int - 출력 결과의 너비.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


출력 결과의 높이를 픽셀 단위로 가져옵니다.


**Returns:**
int - 출력 결과의 높이.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


이미지의 배경 색상을 가져옵니다.


**Returns:**
java.awt.Color - 이미지의 배경 색상.

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


이미지의 배경 색상을 가져옵니다.


**Returns:**
java.lang.String - 이미지의 배경 색상을 0xFFFFFF 형식으로.

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


이미지의 배경 색상을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | 이미지의 배경 색상. |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


이미지의 배경 색상을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | colorName | java.lang.String | 이미지의 배경 색상 이름. |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


렌더링할 그리기 영역을 가져옵니다.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
그
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
및
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) 옵션은 무시됩니다
타일별로 렌더링할 때.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - 렌더링할 그리기 영역 목록.

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


렌더링할 그리기 영역을 설정합니다.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
그
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
및
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) 옵션은 무시됩니다
타일별로 렌더링할 때.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<com.groupdocs.viewer.options.Tile> | 렌더링할 그리기 영역 목록. |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


CAD 문서의 레이아웃을 렌더링할지 여부를 나타냅니다.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
기본적으로 모델만 렌더링됩니다.*


**Returns:**
boolean -  true  레이아웃을 렌더링해야 하는 경우,  false  그 외.

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


CAD 문서의 레이아웃을 렌더링할지 여부를 설정합니다.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
기본적으로 모델만 렌더링됩니다.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  레이아웃을 렌더링하려면,  false  그 외. |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


특정 레이아웃을 렌더링하기 위한 이름을 가져옵니다. 레이아웃 이름은 대소문자를 구분합니다.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
기본적으로 모델만 렌더링됩니다.*


**Returns:**
java.lang.String - 특정 레이아웃을 렌더링하기 위한 이름.

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


특정 레이아웃을 렌더링하기 위한 이름을 설정합니다. 레이아웃 이름은 대소문자를 구분합니다.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
기본적으로 모델만 렌더링됩니다.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 특정 레이아웃을 렌더링하기 위한 이름. |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


렌더링할 CAD 도면 레이어를 가져옵니다.


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 그리기 레이어.

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


렌더링할 CAD 도면 레이어를 가져옵니다.
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 도면 레이어. |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


이 플래그를 true로 설정하면 CAD 제품군의 모든 형식에 대해 특수한 성능 중심 변환 모드가 활성화됩니다. 이 모드에서는 변환 속도가 훨씬 빨라지지만 결과 문서의 품질이 크게 낮아집니다. 기본값은 비활성화(false)입니다. 결과 문서의 품질은 성능을 희생하더라도 가능한 최상의 상태입니다.


**Returns:**
boolean -  true 이면 성능 중심 변환 모드가 활성화된 경우,  false 이면 그렇지 않은 경우.

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


이 플래그를 true로 설정하면 CAD 제품군의 모든 형식에 대해 특수한 성능 중심 변환 모드가 활성화됩니다. 이 모드에서는 변환 속도가 훨씬 빨라지지만 결과 문서의 품질이 크게 낮아집니다. 기본값은 비활성화(false)입니다. 결과 문서의 품질은 성능을 희생하더라도 가능한 최상의 상태입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  은 성능 중심 변환 모드를 활성화하고,  false  은 이를 비활성화합니다. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


이 CadOptions 객체가 다른 객체와 같은지 확인합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | o | java.lang.Object | 비교할 객체. |
|

**Returns:**
boolean -  true 이면 객체가 동일하고,  false 이면 그렇지 않습니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 객체에 대한 해시 코드 값을 계산합니다. 해시 코드는 다음을 기반으로 합니다.
객체의 내부 상태이며 해시 기반 데이터 구조에서 사용됩니다
예: 해시 맵 및 해시 집합.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - 이 객체에 대한 해시 코드 값.

### toString() {#toString--}
```
public String toString()
```


이 객체의 문자열 표현을 반환합니다.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - 이 객체의 문자열 표현.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


이 객체의 문자열 표현을 반환합니다.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | style | org.apache.commons.lang3.builder.ToStringStyle | 문자열 표현을 생성할 때 사용할 ToStringStyle. |
|

**Returns:**
java.lang.String - 지정된 ToStringStyle을 사용하여 이 객체를 문자열로 표현한 결과.

