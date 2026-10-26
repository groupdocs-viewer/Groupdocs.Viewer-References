---
title: "PngViewOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "문서를 PNG 형식으로 렌더링하는 옵션을 제공합니다."
type: docs
weight: 25
url: /ko/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

문서를 PNG 형식으로 렌더링하는 옵션을 제공합니다.

PngViewOptions 클래스는 GroupDocs.Viewer 구성 요소에서 문서를 PNG 형식으로 렌더링하는 것을 제어하는 데 사용할 수 있는 추가 설정 및 매개변수를 캡슐화합니다.

예시 사용법:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PngViewOptions()](#PngViewOptions--) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | PngViewOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | 출력 이미지의 최대 너비를 픽셀 단위로 반환합니다. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 출력 이미지의 최대 너비(픽셀)를 설정합니다. |
| [getMaxHeight()](#getMaxHeight--) | 출력 이미지의 최대 높이를 픽셀 단위로 반환합니다. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 출력 이미지의 최대 높이(픽셀)를 설정합니다. |
| [isExtractText()](#isExtractText--) | 텍스트 추출이 활성화되어 있는지 여부를 결정합니다. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | 텍스트 추출을 활성화하거나 비활성화합니다. |
| [getWidth()](#getWidth--) | 출력 이미지의 너비를 픽셀 단위로 반환합니다. |
| [setWidth(int value)](#setWidth-int-) | 출력 이미지의 너비(픽셀)를 설정합니다. |
| [getHeight()](#getHeight--) | 출력 이미지의 높이를 픽셀 단위로 반환합니다. |
| [setHeight(int value)](#setHeight-int-) | 출력 이미지의 높이를 픽셀 단위로 설정합니다. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | 문서 저장 진행 상황을 추정하기 위한 콜백을 가져옵니다. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | 문서 저장 진행 상황을 추정하기 위한 콜백을 설정합니다. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream 매개변수에 할당된 메서드가 만든 스트림을 해제하는 메서드입니다. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

이 생성자는 출력 파일의 파일 경로 형식으로 "p\_\{0\}.png"를 사용하여 PngViewOptions의 새 인스턴스를 초기화합니다. 출력 파일은 애플리케이션의 현재 작업 디렉터리에 저장됩니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

예를 들어 파일 경로 형식이 'page\_\{0\}.png'인 경우, 출력 파일은 페이지 번호에 따라 'page\_1.png', 'page\_2.png' 등으로 이름이 지정됩니다.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식, 예: 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


PngViewOptions 클래스의 새 인스턴스를 초기화합니다.

예를 들어 파일 경로 형식이 'page\_\{0\}.png'인 경우, 출력 파일은 페이지 번호에 따라 'page\_1.png', 'page\_2.png' 등으로 이름이 지정됩니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | 파일 경로 형식, 예: 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


출력 이미지의 최대 너비를 픽셀 단위로 반환합니다.

이 속성을 사용하여 출력 이미지의 최대 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 너비.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


출력 이미지의 최대 너비(픽셀)를 설정합니다.

이 속성을 사용하여 출력 이미지의 최대 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxWidth | int | 출력 이미지의 최대 너비. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


출력 이미지의 최대 높이를 픽셀 단위로 반환합니다.

이 속성을 사용하여 출력 이미지의 최대 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 높이.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


출력 이미지의 최대 높이(픽셀)를 설정합니다.

이 속성을 사용하여 출력 이미지의 최대 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 해당 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxHeight | int | 출력 이미지의 최대 높이. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


텍스트 추출이 활성화되어 있는지 여부를 결정합니다.

이미지 위에 선택 가능한 텍스트 레이어를 추가하려는 경우 이 옵션이 유용할 수 있습니다. 이 속성을 사용하여 원본 문서에 포함된 텍스트와 해당 좌표를 가져옵니다. 그런 다음 이 데이터를 사용해 이미지 위에 선택 가능한 텍스트를 추가하거나 이미지 기반 렌더링에서 텍스트 검색을 구현할 수 있습니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean - 텍스트 추출이 활성화된 경우 true, 그렇지 않으면 false.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


텍스트 추출을 활성화하거나 비활성화합니다.

이미지 위에 선택 가능한 �스트 레이어를 추가하려는 경우 이 옵션이 유용할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 텍스트 추출을 활성화하려면 true, 비활성화하려면 false. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


출력 이미지의 너비를 픽셀 단위로 반환합니다.

이 속성을 사용하여 출력 이미지의 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 출력 이미지의 너비.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


출력 이미지의 너비(픽셀)를 설정합니다.

이 속성을 사용하여 출력 이미지의 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 출력 이미지의 너비. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


출력 이미지의 높이를 픽셀 단위로 반환합니다.

이 속성을 사용하여 출력 이미지의 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 출력 이미지의 높이.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


출력 이미지의 높이를 픽셀 단위로 설정합니다.

이 속성을 사용하여 출력 이미지의 높이(픽셀)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 출력 이미지의 높이. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


문서 저장 진행 상황을 추정하기 위한 콜백을 가져옵니다.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 문서 저장 진행 상황을 추정하는 콜백입니다.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


문서 저장 진행 상황을 추정하기 위한 콜백을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 문서 저장 진행 상황을 추정하는 콜백입니다. |

