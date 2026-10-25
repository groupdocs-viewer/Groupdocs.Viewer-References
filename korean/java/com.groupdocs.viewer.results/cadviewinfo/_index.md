---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CAD 도면에 대한 보기 정보를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

CAD 도면에 대한 보기 정보를 나타냅니다.


CadViewInfo 인터페이스는 CAD 도면에 특화된 보기 정보를 검색하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서. CAD 도면 레이어에 접근하는 메서드를 제공합니다.


사용 예시:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLayers()](#getLayers--) | CAD 도면의 레이어 목록을 검색합니다. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | CAD 도면의 레이어 목록을 설정합니다. |
|
|  | [getLayouts()](#getLayouts--) | CAD 도면에 포함된 레이아웃 목록을 검색합니다. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | CAD 도면에 포함된 레이아웃 목록을 설정합니다. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


CAD 도면의 레이어 목록을 검색합니다.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 도면의 레이어.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


CAD 도면의 레이어 목록을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 도면에 설정할 레이어. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


CAD 도면에 포함된 레이아웃 목록을 검색합니다.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - CAD 도면의 레이아웃.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


CAD 도면에 포함된 레이아웃 목록을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | CAD 도면에 설정할 레이아웃. |
|

