---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "문서를 HTML 형식으로 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

문서를 HTML 형식으로 렌더링하기 위한 옵션을 제공합니다.


HtmlViewOptions 클래스는 추가 설정 및 매개변수를 캡슐화합니다.
이 설정은 GroupDocs.Viewer 구성 요소에서 문서를 HTML 형식으로 렌더링하는 것을 제어하는 데 사용할 수 있습니다.


자세한 내용은 [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) 및 해당 하위 항목을 참조하십시오.


사용 예시:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | 반응형 렌더링이 활성화되어 있는지 여부를 결정합니다. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | 반응형 렌더링이 활성화될지 여부를 설정합니다. |
|
|  | [isMinify()](#isMinify--) | HTML 콘텐츠 및 HTML 리소스 최소화가 활성화되어 있는지 확인합니다. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | HTML 콘텐츠 및 HTML 리소스 최소화가 활성화될지 여부를 설정합니다. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | 전체 문서를 하나의 HTML 파일로 렌더링하도록 활성화합니다. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | 전체 문서를 하나의 HTML 파일로 렌더링하도록 활성화합니다. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | 출력 이미지의 최대 너비를 픽셀 단위로 반환합니다. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 출력 이미지의 최대 너비(픽셀)를 설정합니다. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | 출력 이미지의 최대 높이를 픽셀 단위로 가져옵니다. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 출력 이미지의 최대 높이(픽셀)를 설정합니다. |
|
|  | [getImageWidth()](#getImageWidth--) | 출력 이미지의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | 출력 이미지의 너비를 픽셀 단위로 설정합니다. |
|
|  | [getImageHeight()](#getImageHeight--) | 단일 이미지를 HTML로 변환할 때 출력 이미지의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | 단일 이미지를 HTML로 변환할 때 출력 이미지의 높이를 픽셀 단위로 설정합니다. |
|
|  | [isForPrinting()](#isForPrinting--) | 출력 HTML이 인쇄용으로 최적화되어야 하는지 확인합니다. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | 출력 HTML이 인쇄용으로 최적화될지 여부를 설정합니다. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | HTML 문서에서 글꼴을 제외할지 여부를 결정합니다. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | HTML 문서에서 글꼴을 제외할지 여부를 설정합니다. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | HTML 문서에서 제외할 글꼴 이름 목록을 검색합니다. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | HTML 문서에서 제외할 글꼴 이름 목록을 설정합니다. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | 스크립트를 포함한 입력 문서를 렌더링할 때, 결과 HTML 문서의 링크에서 JavaScript 소스 코드를 제거하도록 허용합니다. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | 스크립트를 포함한 입력 문서를 렌더링할 때, 결과 HTML 문서의 링크에서 JavaScript 소스 코드를 제거할 권한을 설정합니다. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words 또는 Email 문서 저장 진행 상황을 추정하는 데 사용되는 콜백을 검색합니다. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words 또는 Email 문서 저장 진행 상황을 추정하는 데 사용되는 콜백을 설정합니다. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
클래스.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
클래스.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
클래스.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
|
|  | [forExternalResources()](#forExternalResources--) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
클래스.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | 새 인스턴스를 초기화합니다. |
HtmlViewOptions
클래스.
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


반응형 렌더링이 활성화되어 있는지 여부를 결정합니다.
반응형 웹 페이지는 다양한 화면 크기의 장치에서 잘 표시됩니다.


반응형 디자인은 다양한 장치에서 웹 페이지가 잘 표시되도록 하는 것을 목표로 합니다. 반응형 레이아웃으로 렌더링하려면 이 속성을 true로 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)을 참조하십시오.


**Returns:**
boolean -  true  응답형 렌더링이 활성화된 경우,  false  그렇지 않은 경우.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


반응형 렌더링이 활성화될지 여부를 설정합니다.
반응형 웹 페이지는 다양한 화면 크기의 장치에서 잘 표시됩니다.


반응형 디자인은 다양한 장치에서 웹 페이지가 잘 표시되도록 하는 것을 목표로 합니다. 반응형 레이아웃으로 렌더링하려면 이 속성을 true로 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  응답형 렌더링을 활성화하려면,  false  비활성화하려면. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


HTML 콘텐츠 및 HTML 리소스 최소화가 활성화되어 있는지 확인합니다.


출력 콘텐츠(HTML, CSS 및 SVG)의 압축은 HTML 파일을 최적화하는 방법 중 하나입니다. 이를 수행하려면 이 속성을 true로 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/minify-html/)을 참조하십시오.


**Returns:**
boolean -  true  최소화가 활성화된 경우,  false  그렇지 않은 경우.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


HTML 콘텐츠 및 HTML 리소스 최소화가 활성화될지 여부를 설정합니다.


출력 콘텐츠(HTML, CSS 및 SVG)의 압축은 HTML 파일을 최적화하는 방법 중 하나입니다. 이를 수행하려면 이 속성을 true로 설정하십시오.
코드 예제는 [documentation](../https://docs.groupdocs.com/viewer/java/minify-html/)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  최소화를 활성화하려면,  false  비활성화하려면. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


전체 문서를 하나의 HTML 파일로 렌더링하도록 활성화합니다.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


전체 문서를 하나의 HTML 파일로 렌더링하도록 활성화합니다.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


출력 이미지의 최대 너비를 픽셀 단위로 반환합니다.
***Note:** This value is used when converting a single image to HTML.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.*


**Returns:**
int - 출력 이미지의 최대 너비.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


출력 이미지의 최대 너비(픽셀)를 설정합니다.
***Note:** This value is used when converting a single image to HTML.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageMaxWidth | int | 출력 이미지의 최대 너비. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


출력 이미지의 최대 높이를 픽셀 단위로 가져옵니다.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.*


**Returns:**
int - 출력 이미지의 최대 높이.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


출력 이미지의 최대 높이(픽셀)를 설정합니다.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageMaxHeight | int | 출력 이미지의 최대 높이. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


출력 이미지의 너비를 픽셀 단위로 가져옵니다.


***Note:** This value is applicable only when converting a single image to HTML.*
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.


**Returns:**
int - 출력 이미지의 너비.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


출력 이미지의 너비를 픽셀 단위로 설정합니다.


***Note:** This value is applicable only when converting a single image to HTML.*
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageWidth | int | 출력 이미지의 너비. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


단일 이미지를 HTML로 변환할 때 출력 이미지의 높이를 픽셀 단위로 가져옵니다.


자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.


**Returns:**
int - 출력 이미지의 높이(픽셀 단위).

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


단일 이미지를 HTML로 변환할 때 출력 이미지의 높이를 픽셀 단위로 설정합니다.


자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageHeight | int | 출력 이미지의 높이(픽셀 단위). |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


출력 HTML이 인쇄용으로 최적화되어야 하는지 확인합니다.


이 옵션을 활성화하면 출력 HTML 페이지를 벡터 SVG 형식으로 변환합니다.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/)를 참조하십시오.


**Returns:**
boolean -  true  출력 HTML을 인쇄용으로 최적화해야 하면,  false  그렇지 않으면.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


출력 HTML이 인쇄용으로 최적화될지 여부를 설정합니다.


이 옵션을 활성화하면 출력 HTML 페이지를 벡터 SVG 형식으로 변환합니다.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  출력 HTML을 인쇄용으로 최적화하려면,  false  그렇지 않으면. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


HTML 문서에서 글꼴을 제외할지 여부를 결정합니다.


기본적으로 GroupDocs.Viewer는 문서에 사용된 글꼴을 HTML에 포함합니다. 이를 방지하려면 이 속성을 true 로 설정하십시오.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)를 참조하십시오.


**Returns:**
boolean -  true  글꼴을 제외해야 하면,  false  그렇지 않으면.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


HTML 문서에서 글꼴을 제외할지 여부를 설정합니다.


기본적으로 GroupDocs.Viewer는 문서에 사용된 글꼴을 HTML에 포함합니다. 이를 방지하려면 이 속성을 true 로 설정하십시오.
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  글꼴을 제외하려면,  false  그렇지 않으면. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


HTML 문서에서 제외할 글꼴 이름 목록을 검색합니다.


이 옵션은 프레젠테이션에만 지원됩니다.
HTML 문서에 글꼴을 포함하면 출력 뷰의 안정성이 향상되지만 렌더링 결과의 크기가 증가합니다.
이 옵션을 사용하여 안정성과 출력 크기 사이의 균형을 찾으십시오.
대부분의 시스템에 설치되어 있는 일반적인 글꼴 이름을 포함합니다.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) 옵션이 비활성화되었습니다.*
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)를 참조하십시오.


**Returns:**
java.util.List<java.lang.String> - HTML 문서에서 제외할 글꼴 이름 목록.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


HTML 문서에서 제외할 글꼴 이름 목록을 설정합니다.


이 옵션은 프레젠테이션에만 지원됩니다.
HTML 문서에 글꼴을 포함하면 출력 뷰의 안정성이 향상되지만 렌더링 결과의 크기가 증가합니다.
이 옵션을 사용하여 안정성과 출력 크기 사이의 균형을 찾으십시오.
대부분의 시스템에 설치되어 있는 일반적인 글꼴 이름을 포함합니다.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) 옵션이 비활성화되었습니다.*
자세한 내용과 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/exclude-fonts/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.List<java.lang.String> | HTML 문서에서 제외할 글꼴 이름 목록. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


입력 문서에 스크립트가 포함된 경우, 결과 HTML 문서의 링크에서 JavaScript 소스 코드를 제거하도록 허용합니다. 기본값은 활성화됨(true).


JavaScript 제거에 대한 자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)를 참조하십시오.


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


입력 문서에 스크립트가 포함된 경우, 결과 HTML 문서의 링크에서 JavaScript 소스 코드를 제거하는 권한을 설정합니다. 기본값은 활성화됨(true).


JavaScript 제거에 대한 자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words 또는 Email 문서 저장 진행 상황을 추정하는 데 사용되는 콜백을 검색합니다.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 문서 저장 진행률을 추정하는 데 사용되는 콜백입니다.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words 또는 Email 문서 저장 진행 상황을 추정하는 데 사용되는 콜백을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 문서 저장 진행률을 추정하는 데 사용되는 콜백입니다. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


***Note:** The method takes a 
CreatePageStream
매개변수, 출력 페이지 데이터를 쓰기 위해 스트림을 인스턴스화하는 메서드입니다.*
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰기 위해 사용되는 스트림을 인스턴스화하는 메서드입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰기 위해 사용되는 스트림을 인스턴스화하는 메서드입니다. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) |   createPageStream  매개변수에 할당된 메서드가 만든 스트림을 해제하는 메서드입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
임베디드 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
클래스.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
클래스.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 파일 경로 형식, 예: 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
클래스.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | 파일 경로 형식, 예: 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰기 위해 사용되는 스트림을 인스턴스화하는 메서드입니다. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) |   createPageStream  메서드가 만든 스트림을 해제하는 메서드입니다. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML 리소스의 URL을 생성하는 메서드입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰기 위해 사용되는 스트림을 인스턴스화하는 메서드입니다. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | 출력 HTML 리소스 데이터를 쓰기 위해 사용되는 스트림을 인스턴스화하는 메서드입니다. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML 리소스의 URL을 생성하는 메서드입니다. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) |   createPageStream  메서드가 만든 스트림을 해제하는 메서드입니다. |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) |   createResourceStream  메서드가 만든 스트림을 해제하는 메서드입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | 리소스 URL을 생성하고 출력 HTML 리소스 스트림을 인스턴스화/해제하는 메서드를 구현하는 팩터리입니다. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
클래스.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다. 코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)를 참조하십시오.

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


새 인스턴스를 초기화합니다.
HtmlViewOptions
클래스.


코드 예제는 [문서](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 파일 경로 형식, 예: 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | 리소스 파일 경로 형식, 예: 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | 리소스 URL 형식, 예: 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
