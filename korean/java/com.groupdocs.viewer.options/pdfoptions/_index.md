---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF 문서를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 22
url: /ko/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF 문서를 렌더링하기 위한 옵션을 제공합니다.


PdfOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다
GroupDocs.Viewer 구성 요소에서 PDF 문서 렌더링을 제어합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)을 참조하십시오.


사용 예시:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | 새 인스턴스를 초기화합니다 |
PdfOptions
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | 소스의 텍스트가 HTML에서 이미지로 렌더링되는지 여부를 결정합니다. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | 소스의 텍스트를 HTML에서 이미지로 렌더링할지 여부를 설정합니다. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | 페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 유지하기 위해 문자 그룹화를 비활성화했는지 확인합니다. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | 페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 보장하기 위해 문자 그룹화를 비활성화하는 옵션을 설정합니다. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML로 렌더링할 때 텍스트와 그래픽의 렌더링이 원본 PDF 문서의 z-순서를 따르는지 확인합니다. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML로 렌더링할 때 원본 PDF 문서의 z-순서에 따라 텍스트와 그래픽의 렌더링을 활성화하거나 비활성화합니다. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | 폰트 힌팅이 활성화되어 있는지 여부를 결정합니다. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | 폰트 힌팅을 활성화합니다. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | 소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | 소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다. |
|
|  | [getImageQuality()](#getImageQuality--) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 가져옵니다. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 설정합니다. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸 출력 품질을 향상시키려면 이 옵션을 활성화합니다. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸 출력 품질을 향상시키려면 이 옵션을 활성화합니다. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | 텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 폰트를 교체합니다. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | 텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 폰트를 교체합니다. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제합니다. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제하도록 플래그를 설정합니다. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


새 인스턴스를 초기화합니다
PdfOptions
클래스.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다.


텍스트와 이미지를 HTML로 복사하는 것을 방지하는 보호 기능이 있는 PDF 파일을 렌더링할 때, GroupDocs.Viewer는 HTML BODY 태그에 'inert' HTML 속성을 추가합니다.
이 옵션의 기본값은
false
.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)를 참조하십시오.


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다.


텍스트와 이미지를 HTML로 복사하는 것을 방지하는 보호 기능이 있는 PDF 파일을 렌더링할 때, GroupDocs.Viewer는 HTML BODY 태그에 'inert' HTML 속성을 추가합니다.
이 옵션의 기본값은
false
.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


소스의 텍스트가 HTML에서 이미지로 렌더링되는지 여부를 결정합니다.


이 옵션이 설정된 경우
true
, 텍스트가 출력 HTML에서 이미지로 렌더링됩니다.
텍스트를 선택할 수 없게 하거나 문자 렌더링을 수정하여 HTML이 PDF와 같이 보이도록 이 옵션을 활성화합니다.
이 옵션은 HTML로 렌더링할 때 지원됩니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  텍스트가 HTML에서 이미지로 렌더링되는 경우,  false  그렇지 않은 경우.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


소스의 텍스트를 HTML에서 이미지로 렌더링할지 여부를 설정합니다.


이 옵션이 설정된 경우
true
, 텍스트가 출력 HTML에서 이미지로 렌더링됩니다.
텍스트를 선택할 수 없게 하거나 문자 렌더링을 수정하여 HTML이 PDF와 같이 보이도록 이 옵션을 활성화합니다.
이 옵션은 HTML로 렌더링할 때 지원됩니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  텍스트를 HTML에서 이미지로 렌더링하려면,  false  그렇지 않은 경우. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 유지하기 위해 문자 그룹화를 비활성화했는지 확인합니다.
이 옵션을 활성화하면, 문자가 그룹화 없이 렌더링되어 최대 정밀도를 보장합니다.


***Note:** By default, character grouping is enabled.*
PDF 파일을 변환할 때, GroupDocs.Viewer는 개별 문자를 단어로 그룹화하여 렌더링 성능을 향상시킵니다. 문서에 상형문자나 특수 기호가 포함된 경우, 보다 정밀한 레이아웃을 위해 문자 그룹화를 금지하고 싶을 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)를 참조하십시오.


**Returns:**
boolean -  true  문자 그룹화가 비활성화된 경우,  false  그렇지 않은 경우.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 보장하기 위해 문자 그룹화를 비활성화하는 옵션을 설정합니다.
값을 설정하여 이 옵션을 활성화하면
true
, 문자 그룹화가 비활성화되어 최대 정밀도를 보장합니다.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
PDF 파일을 변환할 때, GroupDocs.Viewer는 개별 문자를 단어로 그룹화하여 렌더링 성능을 향상시킵니다. 문서에 상형문자나 특수 기호가 포함된 경우, 보다 정밀한 레이아웃을 위해 문자 그룹화를 금지하고 싶을 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  문자 그룹화를 비활성화하려면,  false  활성화하려면. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML로 렌더링할 때 텍스트와 그래픽의 렌더링이 원본 PDF 문서의 z-순서를 따르는지 확인합니다.
반환하여 이 옵션을 활성화하면
true
, 텍스트와 그래픽이 원본 PDF 문서의 z-순서에 따라 렌더링됩니다.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
기본적으로, GroupDocs.Veiewer는 텍스트와 그래픽을 HTML에서 단일 레이어로 렌더링합니다. 이 옵션을 사용하면 객체를 원본 파일과 동일한 순서대로 배치할 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)를 참조하십시오.


**Returns:**
boolean -  true  레이어드 렌더링이 활성화된 경우,  false  그렇지 않은 경우.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML로 렌더링할 때 원본 PDF 문서의 z-순서에 따라 텍스트와 그래픽의 렌더링을 활성화하거나 비활성화합니다.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
기본적으로, GroupDocs.Veiewer는 텍스트와 그래픽을 HTML에서 단일 레이어로 렌더링합니다. 이 옵션을 사용하면 객체를 원본 파일과 동일한 순서대로 배치할 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  레이어드 렌더링을 활성화하려면,  false  비활성화하려면. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


폰트 힌팅이 활성화되었는지 여부를 결정합니다. 폰트 힌팅은 외곽선 폰트의 표시를 조정합니다.
이 옵션은 원본 문서에서 사용할 때 TrueType (TTF) 폰트에만 지원됩니다.


***Note:** This option is supported when rendering into PNG or JPG formats.*
폰트 힌팅은 외곽선 폰트가 표시되는 방식을 조정합니다. 원본 문서에서 사용되는 TTF 폰트에만 적용됩니다. 이 옵션은 PNG 또는 JPG 형식으로 렌더링할 때 사용할 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)를 참조하십시오.


**Returns:**
boolean -  true  폰트 힌팅이 활성화된 경우,  false  그렇지 않은 경우.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


폰트 힌팅을 활성화합니다. 폰트 힌팅은 외곽선 폰트의 표시를 조정하며, 원본 문서에서 사용할 때 TrueType (TTF) 폰트에만 지원됩니다.


***Note:** This option is supported when rendering into PNG or JPG formats.*
폰트 힌팅은 외곽선 폰트가 표시되는 방식을 조정합니다. 원본 문서에서 사용되는 TTF 폰트에만 적용됩니다. 이 옵션은 PNG 또는 JPG 형식으로 렌더링할 때 사용할 수 있습니다. 기본값은 false입니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  폰트 힌팅을 활성화하려면,  false  비활성화하려면. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
기본적으로, GroupDocs.Viewer는 더 나은 렌더링 품질을 위해 출력 이미지 페이지 크기를 계산합니다. 이 옵션을 활성화하면 출력 페이지가 원본 PDF 문서의 페이지 크기(픽셀 단위)와 동일하게 유지됩니다. 기본값은 false입니다.
이 옵션은 PNG 또는 JPG 형식으로 렌더링할 때 사용할 수 있습니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)를 참조하십시오.


**Returns:**
boolean -  true  옵션이 활성화된 경우,  false  그렇지 않은 경우.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
기본적으로, GroupDocs.Viewer는 더 나은 렌더링 품질을 위해 출력 이미지 페이지 크기를 계산합니다. 이 옵션을 활성화하면 출력 페이지가 원본 PDF 문서의 페이지 크기(픽셀 단위)와 동일하게 유지됩니다. 기본값은 false입니다.
이 옵션은 PNG 또는 JPG 형식으로 렌더링할 때 사용할 수 있습니다.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  원본 페이지 크기로 렌더링을 활성화하려면,  false  그렇지 않으면. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 가져옵니다. 기본값은 Low입니다.


이 옵션을 true로 설정하면 GroupDocs.Viewer는 HTML 출력에서 텍스트를 이미지로 렌더링합니다. 이렇게 하면 텍스트를 선택할 수 없게 되고 문자 렌더링이 향상되어 HTML에서 PDF와 같은 모양을 보장합니다. 기본값은 false입니다.
이 옵션은 HTML로 렌더링할 때 사용할 수 있습니다.
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)를 참조하세요.


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 설정합니다. 기본값은 Low입니다.


이 옵션을 true로 설정하면 GroupDocs.Viewer는 HTML 출력에서 텍스트를 이미지로 렌더링합니다. 이렇게 하면 텍스트를 선택할 수 없게 되고 문자 렌더링이 향상되어 HTML에서 PDF와 같은 모양을 보장합니다. 기본값은 false입니다.
이 옵션은 HTML로 렌더링할 때 사용할 수 있습니다.
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다.
출력 HTML이 원본 PDF와 동일하게 보이도록 문서는 기본적으로 고정 레이아웃으로 HTML에 렌더링됩니다.
고정 레이아웃으로 렌더링하면 출력 HTML의 크기가 고정되어 요소가 창 크기에 관계없이 동일한 위치에 유지됩니다.
유동 레이아웃으로 HTML을 렌더링하려면 이 속성을 false로 설정하세요.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF 및 EPUB 문서는 원본 문서의 모양을 유지하기 위해 처음에 고정 레이아웃으로 HTML에 렌더링됩니다. 이 고정 레이아웃은 모든 HTML 요소가 지정된 크기의 컨테이너 내에서 정확한 위치를 갖는다는 의미입니다. 브라우저 창 크기를 조정해도 문서 내 요소의 위치와 크기에 영향을 주지 않습니다.
이 옵션은 HTML로 렌더링할 때만 사용할 수 있습니다. 기본값은 true입니다. 유동 레이아웃으로 렌더링하려면 이 속성을 false로 설정하세요.


사용 예시:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - 고정 레이아웃인 경우 true

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다.
출력 HTML이 원본 PDF와 동일하게 보이도록 문서는 기본적으로 고정 레이아웃으로 HTML에 렌더링됩니다.
고정 레이아웃으로 렌더링하면 출력 HTML의 크기가 고정되어 요소가 창 크기에 관계없이 동일한 위치에 유지됩니다.
유동 레이아웃으로 HTML을 렌더링하려면 이 속성을 false로 설정하세요.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF 및 EPUB 문서는 원본 문서의 모양을 유지하기 위해 처음에 고정 레이아웃으로 HTML에 렌더링됩니다. 이 고정 레이아웃은 모든 HTML 요소가 지정된 크기의 컨테이너 내에서 정확한 위치를 갖는다는 의미입니다. 브라우저 창 크기를 조정해도 문서 내 요소의 위치와 크기에 영향을 주지 않습니다.
이 옵션은 HTML로 렌더링할 때만 사용할 수 있습니다. 기본값은 true입니다. 유동 레이아웃으로 렌더링하려면 이 속성을 false로 설정하세요.


사용 예시:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fixedLayout | boolean | 고정 레이아웃인 경우 true |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸 출력 품질을 향상시키려면 이 옵션을 활성화합니다.


이 옵션은 [PDF 및 페이지 레이아웃 파일 형식](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats)을 HTML로 렌더링할 때 임베디드 및 외부 리소스와 함께 지원됩니다.


기본적으로 PDF 및 페이지 레이아웃 파일로 렌더링할 때 모든 이미지가 하나의 PNG 이미지로 렌더링됩니다. 렌더링된 PNG 이미지는 출력 HTML 문서의 배경으로 사용됩니다.


자세히 알아보기:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  이미지가 SVG로 래핑된 경우 true,  그렇지 않으면 false.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


출력 HTML 문서에서 각 이미지를 SVG 태그로 감싸 출력 품질을 향상시키려면 이 옵션을 활성화합니다.


이 옵션은 [PDF 및 페이지 레이아웃 파일 형식](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats)을 HTML로 렌더링할 때 임베디드 및 외부 리소스와 함께 지원됩니다.


기본적으로 PDF 및 페이지 레이아웃 파일로 렌더링할 때 모든 이미지가 하나의 PNG 이미지로 렌더링됩니다. 렌더링된 PNG 이미지는 출력 HTML 문서의 배경으로 사용됩니다.


자세히 알아보기:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | 이미지를 SVG로 래핑해야 하는 경우 true,  그렇지 않으면 false. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 폰트를 교체합니다.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 폰트를 교체합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | analyzeFonts | boolean | 글꼴을 표시해야 하는 경우 true, 그렇지 않으면 false. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제합니다.


폰에 대한 많은 작업은 해당 폰트의 라이선스가 이러한 작업을 금지하는 경우 실행할 수 없습니다.
예를 들어, 라이선스 규정이 해당 폰트의 임베딩을 금지하는 경우 일부 폰트를 PDF 문서에 삽입할 수 없습니다.
이 플래그를 사용할 때 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이 모든 책임을 진다는 의미입니다
자신에게 발생할 수 있는 라이선스/법 위반에 대해. 따라서 자신이 위험을 감수해야 합니다. 사용을 강력히 권장합니다
이 플래그는 저작권법을 위반하고 있지 않다는 확신이 완전할 때만 사용하십시오. 기본값은 false입니다.
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)를 참조하십시오.


사용 예시:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제하도록 플래그를 설정합니다.


폰에 대한 많은 작업은 해당 폰트의 라이선스가 이러한 작업을 금지하는 경우 실행할 수 없습니다.
예를 들어, 라이선스 규정이 해당 폰트의 임베딩을 금지하는 경우 일부 폰트를 PDF 문서에 삽입할 수 없습니다.
이 플래그를 사용할 때 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이 모든 책임을 진다는 의미입니다
자신에게 발생할 수 있는 라이선스/법 위반에 대해. 따라서 자신이 위험을 감수해야 합니다. 사용을 강력히 권장합니다
이 플래그는 저작권법을 위반하고 있지 않다는 확신이 완전할 때만 사용하십시오. 기본값은 false입니다.
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)를 참조하십시오.


사용 예시:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

