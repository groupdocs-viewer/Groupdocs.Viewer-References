---
title: "PdfOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "PDF 문서 렌더링 옵션을 제공합니다."
type: docs
weight: 22
url: /ko/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF 문서 렌더링 옵션을 제공합니다.

PdfOptions 클래스는 GroupDocs.Viewer 구성 요소에서 PDF 문서 렌더링을 제어하는 데 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 [documentation][].

예시 사용법:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | PdfOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | 소스의 텍스트가 HTML에서 이미지로 렌더링되는지 여부를 결정합니다. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | 소스의 텍스트를 HTML에서 이미지로 렌더링할지 여부를 설정합니다. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | 페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 유지하기 위해 문자 그룹화가 비활성화되어 있는지 확인합니다. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | 페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 보장하기 위해 문자 그룹화를 비활성화하는 옵션을 설정합니다. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML로 렌더링할 때 텍스트와 그래픽의 렌더링이 원본 PDF 문서의 Z-순서를 따르는지 확인합니다. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML로 렌더링할 때 텍스트와 그래픽을 원본 PDF 문서의 Z-순서에 따라 렌더링하도록 활성화하거나 비활성화합니다. |
| [isEnableFontHinting()](#isEnableFontHinting--) | 폰트 힌팅이 활성화되어 있는지 여부를 결정합니다. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | 폰트 힌팅을 활성화합니다. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | 소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | 소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다. |
| [getImageQuality()](#getImageQuality--) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 가져옵니다. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 설정합니다. |
| [isFixedLayout()](#isFixedLayout--) | PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF는 고정 형식이므로 모든 요소가 페이지 내에 특정 위치를 가집니다. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 출력 품질을 향상시키기 위해 출력 HTML 문서의 각 이미지를 SVG 태그로 감싸는 옵션을 활성화합니다. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 출력 품질을 향상시키기 위해 출력 HTML 문서의 각 이미지를 SVG 태그로 감싸는 옵션을 활성화합니다. |
| [isFixLinkIssue()](#isFixLinkIssue--) | 전체 HTML 페이지 내용이 링크인 경우 문제를 해결하려고 시도합니다. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | 전체 HTML 페이지 내용이 링크인 경우 문제를 해결하려고 시도합니다. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | 텍스트의 모든 문자를 표시할 수 있도록 필요한 경우 폰트를 교체합니다. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | 텍스트의 모든 문자를 표시할 수 있도록 필요한 경우 폰트를 교체합니다. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제합니다. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 현재 XPS/OXPS 문서의 모든 글꼴에 대한 라이선스 제한을 해제하도록 플래그를 설정합니다. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


PdfOptions 클래스의 새 인스턴스를 초기화합니다.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다.

텍스트와 이미지를 복사하는 것을 방지하는 보호가 적용된 PDF 파일을 HTML로 렌더링할 때, GroupDocs.Viewer는 HTML BODY 태그에 'inert' HTML 속성을 추가합니다. 이 옵션의 기본값은  false  입니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML로 렌더링할 때 콘텐츠 복사 보호를 해제합니다.

텍스트와 이미지를 복사하는 것을 방지하는 보호가 적용된 PDF 파일을 HTML로 렌더링할 때, GroupDocs.Viewer는 HTML BODY 태그에 'inert' HTML 속성을 추가합니다. 이 옵션의 기본값은  false  입니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


소스의 텍스트가 HTML에서 이미지로 렌더링되는지 여부를 결정합니다.

이 옵션을  true  로 설정하면 텍스트가 출력 HTML에서 이미지로 렌더링됩니다. 텍스트를 선택할 수 없게 하거나 문자 렌더링을 수정하고 HTML을 PDF와 같이 보이게 하려면 이 옵션을 활성화하십시오. 이 옵션은 HTML로 렌더링할 때 지원됩니다.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  : 텍스트가 HTML에서 이미지로 렌더링되는 경우,  false  : 그 외의 경우.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


소스의 텍스트를 HTML에서 이미지로 렌더링할지 여부를 설정합니다.

이 옵션을  true  로 설정하면 텍스트가 출력 HTML에서 이미지로 렌더링됩니다. 텍스트를 선택할 수 없게 하거나 문자 렌더링을 수정하고 HTML을 PDF와 같이 보이게 하려면 이 옵션을 활성화하십시오. 이 옵션은 HTML로 렌더링할 때 지원됩니다.

***Note:** The default value is  false .*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderTextAsImage | boolean | true  : 텍스트를 HTML에서 이미지로 렌더링,  false  : 그 외. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 유지하기 위해 문자 그룹화가 비활성화되어 있는지 확인합니다. 이 옵션이 활성화되면 문자가 그룹화 없이 렌더링되어 최대 정밀도가 보장됩니다.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean -  true  : 문자 그룹화가 비활성화된 경우,  false  : 그 외.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


페이지를 렌더링할 때 문자 위치 지정의 최대 정밀도를 보장하기 위해 문자 그룹화를 비활성화하는 옵션을 설정합니다. 값을  true  로 설정하여 이 옵션을 활성화하면 문자 그룹화가 비활성화되어 최대 정밀도가 보장됩니다.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  : 문자 그룹화를 비활성화,  false  : 활성화. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML로 렌더링할 때 텍스트와 그래픽의 렌더링이 원본 PDF 문서의 z-순서를 따르는지 확인합니다. 이 옵션을  true  로 설정하면 텍스트와 그래픽이 원본 PDF 문서의 z-순서에 따라 렌더링됩니다.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean -  true  : 레이어드 렌더링이 활성화된 경우,  false  : 그 외.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML로 렌더링할 때 텍스트와 그래픽을 원본 PDF 문서의 Z-순서에 따라 렌더링하도록 활성화하거나 비활성화합니다.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  : 레이어드 렌더링 활성화,  false  : 비활성화. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


폰트 힌팅이 활성화되어 있는지 여부를 결정합니다. 폰트 힌팅은 외곽선 폰트의 표시를 조정합니다. 이 옵션은 소스 문서에서 TrueType (TTF) 폰트에만 적용됩니다.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean -  true  : 폰트 힌팅이 활성화된 경우,  false  : 그 외.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


폰트 힌팅을 활성화합니다. 폰트 힌팅은 외곽선 폰트의 표시를 조정하며, 소스 문서에서 TrueType (TTF) 폰트에만 적용됩니다.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  : 폰트 힌팅 활성화,  false  : 비활성화. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean -  true  : 옵션이 활성화된 경우,  false  : 그 외.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


소스 PDF 문서의 페이지 크기와 동일한 픽셀 크기로 페이지를 렌더링하도록 활성화합니다.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true  : 원본 페이지 크기로 렌더링 활성화,  false  : 그 외. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 가져옵니다. 기본값은 Low 입니다.

이 옵션을 true 로 설정하면 GroupDocs.Viewer는 HTML 출력에서 텍스트를 이미지로 렌더링합니다. 이렇게 하면 텍스트를 선택할 수 없게 되고 문자 렌더링이 향상되어 HTML에서 PDF와 같은 모습을 보장합니다. 기본값은 false 입니다. 이 옵션은 HTML 렌더링에 사용할 수 있습니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질을 설정합니다. 기본값은 Low 입니다.

이 옵션을 true 로 설정하면 GroupDocs.Viewer는 HTML 출력에서 텍스트를 이미지로 렌더링합니다. 이렇게 하면 텍스트를 선택할 수 없게 되고 문자 렌더링이 향상되어 HTML에서 PDF와 같은 모습을 보장합니다. 기본값은 false 입니다. 이 옵션은 HTML 렌더링에 사용할 수 있습니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML로 렌더링할 때 이미지 리소스의 출력 이미지 품질. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF는 고정 형식이므로 모든 요소가 페이지의 특정 위치에 있습니다. 출력 HTML이 원본 PDF와 동일하게 보이도록 문서는 기본적으로 고정 레이아웃으로 HTML에 렌더링됩니다. 고정 레이아웃으로 렌더링하면 출력 HTML의 크기가 고정되어 창 크기에 관계없이 요소가 동일한 위치에 유지됩니다. 유동 레이아웃으로 HTML을 렌더링하려면 이 속성을 false로 설정하십시오.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

예시 사용법:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - 고정 레이아웃인 경우 true
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF는 고정 형식이므로 모든 요소가 페이지의 특정 위치에 있습니다. 출력 HTML이 원본 PDF와 동일하게 보이도록 문서는 기본적으로 고정 레이아웃으로 HTML에 렌더링됩니다. 고정 레이아웃으로 렌더링하면 출력 HTML의 크기가 고정되어 창 크기에 관계없이 요소가 동일한 위치에 유지됩니다. 유동 레이아웃으로 HTML을 렌더링하려면 이 속성을 false로 설정하십시오.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

예시 사용법:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixedLayout | boolean | 고정 레이아웃인 경우 true |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


출력 품질을 향상시키기 위해 출력 HTML 문서의 각 이미지를 SVG 태그로 감싸는 옵션을 활성화합니다.

이 옵션은 임베디드 및 외부 리소스를 사용하여 HTML로 렌더링할 때 [PDF 및 페이지 레이아웃 파일 형식][]을(를) 지원합니다.

기본적으로 PDF 및 페이지 레이아웃 파일로 렌더링할 때 모든 이미지가 하나의 PNG 이미지로 렌더링됩니다. 렌더링된 PNG 이미지는 출력 HTML 문서의 배경으로 사용됩니다.

자세히 보기:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean - 이미지가 SVG로 래핑된 경우 true, 그렇지 않으면 false
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


출력 품질을 향상시키기 위해 출력 HTML 문서의 각 이미지를 SVG 태그로 감싸는 옵션을 활성화합니다.

이 옵션은 임베디드 및 외부 리소스를 사용하여 HTML로 렌더링할 때 [PDF 및 페이지 레이아웃 파일 형식][]을(를) 지원합니다.

기본적으로 PDF 및 페이지 레이아웃 파일로 렌더링할 때 모든 이미지가 하나의 PNG 이미지로 렌더링됩니다. 렌더링된 PNG 이미지는 출력 HTML 문서의 배경으로 사용됩니다.

자세히 보기:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| wrapImagesInSvg | boolean | 이미지를 SVG로 래핑해야 하는 경우 true, 그렇지 않으면 false |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


전체 HTML 페이지 내용이 링크인 경우 문제를 해결하려고 시도합니다. 입력 형식이 PDF이고 출력 형식이 HTML(임베디드 또는 외부 리소스)인 경우에만 작동합니다. 기본적으로 비활성화되어 있습니다(false). 무엇을 왜 하는지 확실히 알 때만 켜십시오. 이 옵션을 켜면 문서 처리 시간이 증가합니다.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


전체 HTML 페이지 내용이 링크인 경우 문제를 해결하려고 시도합니다. 입력 형식이 PDF이고 출력 형식이 HTML(임베디드 또는 외부 리소스)인 경우에만 작동합니다. 기본적으로 비활성화되어 있습니다(false). 무엇을 왜 하는지 확실히 알 때만 켜십시오. 이 옵션을 켜면 문서 처리 시간이 증가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixLinkIssue | boolean | 문제를 해결해야 하는 경우 true, 그렇지 않으면 false |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


텍스트의 모든 문자를 표시할 수 있도록 필요한 경우 폰트를 교체합니다.

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


텍스트의 모든 문자를 표시할 수 있도록 필요한 경우 폰트를 교체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| analyzeFonts | boolean | 글꼴을 표시해야 하는 경우 true, 그렇지 않으면 false |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


현재 XPS/OXPS 문서의 모든 폰트에 대한 라이선스 제한을 해제합니다.

많은 글꼴 관련 작업은 해당 글꼴의 라이선스가 이러한 작업을 금지하는 경우 실행할 수 없습니다. 예를 들어, 라이선스 규정이 해당 글꼴의 임베딩을 금지하는 경우 일부 글꼴을 PDF 문서에 임베드할 수 없습니다. 이 플래그를 사용할 때는 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이 가능한 라이선스/법 위반에 대한 모든 책임을 스스로 지게 된다는 의미입니다. 따라서 자체 위험을 감수해야 합니다. 저작권법을 위반하지 않는다는 확신이 있을 때만 이 플래그를 사용하는 것이 강력히 권장됩니다. 기본값은 false입니다. 코드 예제는 [문서][]를 참조하십시오.

예시 사용법:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


현재 XPS/OXPS 문서의 모든 글꼴에 대한 라이선스 제한을 해제하도록 플래그를 설정합니다.

많은 글꼴 관련 작업은 해당 글꼴의 라이선스가 이러한 작업을 금지하는 경우 실행할 수 없습니다. 예를 들어, 라이선스 규정이 해당 글꼴의 임베딩을 금지하는 경우 일부 글꼴을 PDF 문서에 임베드할 수 없습니다. 이 플래그를 사용할 때는 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이 가능한 라이선스/법 위반에 대한 모든 책임을 스스로 지게 된다는 의미입니다. 따라서 자체 위험을 감수해야 합니다. 저작권법을 위반하지 않는다는 확신이 있을 때만 이 플래그를 사용하는 것이 강력히 권장됩니다. 기본값은 false입니다. 코드 예제는 [문서][]를 참조하십시오.

예시 사용법:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

