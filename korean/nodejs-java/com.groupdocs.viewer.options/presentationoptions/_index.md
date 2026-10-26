---
title: "PresentationOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "프레젠테이션 렌더링 옵션을 제공합니다."
type: docs
weight: 26
url: /ko/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

프레젠테이션 렌더링 옵션을 제공합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Presentation 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Presentation 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다. |
| [getResolution()](#getResolution--) | 프레젠테이션 내부 이미지의 해상도 (HTML/PDF 렌더링 전용). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | 프레젠테이션 내부 이미지의 해상도 (HTML/PDF 렌더링 전용). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Presentation 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다.

이 모드에서는 Presentation 파일이 SVG 이미지 없이 순수 HTML/CSS 마크업으로 렌더링됩니다. 기본적으로 이 기능은 비활성화되어 있습니다 (false). 이 옵션이 활성화되지 않으면 기존 SVG 기반 HTML 렌더러가 사용됩니다.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Presentation 문서에 대한 새로운 HTML 렌더링 모드를 활성화합니다.

이 모드에서는 Presentation 파일이 SVG 이미지 없이 순수 HTML/CSS 마크업으로 렌더링됩니다. 기본적으로 이 기능은 비활성화되어 있습니다 (false). 이 옵션이 활성화되지 않으면 기존 SVG 기반 HTML 렌더러가 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


프레젠테이션 내부 이미지의 해상도 (HTML/PDF 렌더링 전용).

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


프레젠테이션 내부 이미지의 해상도 (HTML/PDF 렌더링 전용).

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

