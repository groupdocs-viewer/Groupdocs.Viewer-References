---
title: "ViewInfoOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "뷰에 대한 정보를 검색하는 데 사용되는 옵션을 제공합니다."
type: docs
weight: 34
url: /ko/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

뷰에 대한 정보를 검색하는 데 사용되는 옵션을 제공합니다.

ViewInfoOptions 클래스는 GroupDocs.Viewer 구성 요소에서 뷰에 대한 정보를 검색하는 데 사용할 수 있는 추가 설정 및 매개변수를 캡슐화합니다.

예시 사용법:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isExtractText()](#isExtractText--) | 텍스트 추출이 활성화되어 있는지 여부를 나타냅니다. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | 텍스트 추출이 활성화되어 있는지 여부를 나타내는 플래그를 설정합니다. |
| [getMaxWidth()](#getMaxWidth--) | PNG/JPG로 렌더링하기 위한 출력 이미지의 최대 너비를 반환합니다. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 출력 이미지의 최대 너비를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용). |
| [getMaxHeight()](#getMaxHeight--) | PNG/JPG로 렌더링하기 위한 출력 이미지의 최대 높이를 반환합니다. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 출력 이미지의 최대 높이를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용). |
| [getWidth()](#getWidth--) | 출력 이미지의 너비(픽셀 단위, PNG/JPG 렌더링 전용). |
| [setWidth(int width)](#setWidth-int-) | 출력 이미지의 너비(픽셀 단위, PNG/JPG 렌더링 전용). |
| [getHeight()](#getHeight--) | 출력 이미지의 높이(픽셀 단위, PNG/JPG 렌더링 전용). |
| [setHeight(int height)](#setHeight-int-) | 출력 이미지의 높이(픽셀 단위, PNG/JPG 렌더링 전용). |
| [forHtmlView()](#forHtmlView--) | HTML로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | HTML로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forJpgView()](#forJpgView--) | JPG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | JPG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forPngView()](#forPngView--) | PNG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | PNG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forPdfView()](#forPdfView--) | PDF로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다. |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | PdfViewOptions 객체를 기반으로 [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) 클래스의 새 인스턴스를 초기화합니다. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


텍스트 추출이 활성화되어 있는지 여부를 나타냅니다.

이 속성을 사용하여 소스 문서에 포함된 텍스트와 해당 좌표를 가져올 수 있습니다. 그런 다음 이 데이터를 사용하여 이미지 위에 선택 가능한 텍스트를 추가하거나 이미지 기반 렌더링에서 텍스트 검색을 구현할 수 있습니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean - 텍스트 추출이 활성화된 경우 True, 그렇지 않으면 false.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


텍스트 추출이 활성화되어 있는지 여부를 나타내는 플래그를 설정합니다.

이 속성을 사용하여 소스 문서에 포함된 텍스트와 해당 좌표를 가져올 수 있습니다. 그런 다음 이 데이터를 사용하여 이미지 위에 선택 가능한 텍스트를 추가하거나 이미지 기반 렌더링에서 텍스트 검색을 구현할 수 있습니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| extractText | boolean | 텍스트 추출을 활성화하려면 True, 비활성화하려면 false. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG로 렌더링하기 위한 출력 이미지의 최대 너비를 반환합니다.

이 속성을 사용하여 출력 이미지의 최대 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 너비.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


출력 이미지의 최대 너비를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 최대 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxWidth | int | 출력 이미지의 최대 너비. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG로 렌더링하기 위한 출력 이미지의 최대 높이를 반환합니다.

이 속성을 사용하여 출력 이미지의 최대 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 높이.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


출력 이미지의 최대 높이를 설정합니다(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 최대 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxHeight | int | 출력 이미지의 최대 높이. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


출력 이미지의 너비(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - 이미지의 너비.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


출력 이미지의 너비(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| width | int | 이미지의 너비. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


출력 이미지의 높이(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - 이미지의 높이.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


출력 이미지의 높이(픽셀 단위, PNG/JPG 렌더링 전용).

이 속성을 사용하여 출력 이미지의 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| height | int | 이미지의 높이. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


HTML로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


HTML로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderSinglePage | boolean | HTML 콘텐츠를 단일 페이지에 렌더링하도록 활성화합니다. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


JPG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


JPG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| extractText | boolean | 텍스트 추출을 활성화합니다. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


PNG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


PNG로 렌더링할 때 뷰에 대한 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| extractText | boolean | 텍스트 추출을 활성화합니다. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML 보기 옵션. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG 보기 옵션. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) 객체를 기반으로 ViewInfoOptions 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG 보기 옵션. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


PdfViewOptions 객체를 기반으로 [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF 보기 옵션. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
