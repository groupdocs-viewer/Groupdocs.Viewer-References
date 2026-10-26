---
title: "JpgViewOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "문서를 JPG 형식으로 렌더링하는 옵션을 제공합니다."
type: docs
weight: 17
url: /ko/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

문서를 JPG 형식으로 렌더링하는 옵션을 제공합니다.

JpgViewOptions 클래스는 GroupDocs.Viewer 구성 요소에서 문서를 JPG 형식으로 렌더링하는 데 사용할 수 있는 추가 설정 및 매개변수를 캡슐화합니다.

예시 사용법:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | JpgViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | JpgViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | JpgViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [JpgViewOptions()](#JpgViewOptions--) | 출력 파일의 파일 경로 형식으로 "p\\_\\{0\\}.jpg"를 사용하여 JpgViewOptions의 새 인스턴스를 초기화합니다. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | JpgViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | JpgViewOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | 출력 이미지의 최대 너비(픽셀)를 가져옵니다. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 출력 이미지의 최대 너비(픽셀)를 설정합니다. |
| [getMaxHeight()](#getMaxHeight--) | 출력 이미지의 최대 높이를 픽셀 단위로 가져옵니다. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 출력 이미지의 최대 높이(픽셀)를 설정합니다. |
| [getQuality()](#getQuality--) | 출력 이미지의 품질을 가져옵니다. |
| [setQuality(byte value)](#setQuality-byte-) | 출력 이미지의 품질을 설정합니다. |
| [isExtractText()](#isExtractText--) | 텍스트 추출을 활성화합니다. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | 텍스트 추출을 활성화하거나 비활성화합니다. |
| [getWidth()](#getWidth--) | 출력 이미지의 너비를 픽셀 단위로 가져옵니다. |
| [setWidth(int value)](#setWidth-int-) | 출력 이미지의 너비(픽셀)를 설정합니다. |
| [getHeight()](#getHeight--) | 출력 이미지의 높이(픽셀)를 가져옵니다. |
| [setHeight(int value)](#setHeight-int-) | 출력 이미지의 높이를 픽셀 단위로 설정합니다. |
| [getPageStreamFactory()](#getPageStreamFactory--) | 출력 페이지 스트림을 생성 및 해제하는 메서드를 구현하는 팩토리를 가져옵니다. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words 또는 Email 문서의 저장 진행 상황을 추정하기 위한 콜백을 가져옵니다. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words 또는 Email 문서의 저장 진행 상황을 추정하기 위한 콜백을 설정합니다. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


JpgViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


JpgViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream 매개변수에 전달된 대리자에 할당된 메서드가 만든 스트림을 해제하는 메서드입니다. |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


JpgViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


출력 파일의 파일 경로 형식으로 "p\\_\\{0\\}.jpg"를 사용하여 JpgViewOptions의 새 인스턴스를 초기화합니다. 출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


JpgViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 파일 경로 형식, 예: 'page\\_\\{0\\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


JpgViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | 파일 경로 형식, 예: 'page\\_\\{0\\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


출력 이미지의 최대 너비(픽셀)를 가져옵니다.

이 속성을 사용하여 최대 출력 이미지 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을(를) 확인하십시오. \#setWidth(int).setWidth(int) 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 너비.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


출력 이미지의 최대 너비(픽셀)를 설정합니다.

이 속성을 사용하여 최대 출력 이미지 너비(픽셀)를 설정합니다. 코드 예제는 [documentation][]을(를) 확인하십시오. \#setWidth(int).setWidth(int) 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxWidth | int | 출력 이미지의 최대 너비. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


출력 이미지의 최대 높이를 픽셀 단위로 가져옵니다.

이 속성을 사용하여 최대 출력 이미지 높이(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. \#setHeight(int).setHeight(int) 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 출력 이미지의 최대 높이.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


출력 이미지의 최대 높이(픽셀)를 설정합니다.

이 속성을 사용하여 최대 출력 이미지 높이(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. \#setHeight(int).setHeight(int) 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxHeight | int | 출력 이미지의 최대 높이. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


출력 이미지의 품질을 가져옵니다.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - 출력 이미지의 품질.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


출력 이미지의 품질을 설정합니다.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte | 출력 이미지의 품질. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


텍스트 추출을 활성화합니다.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean - 텍스트 추출이 활성화된 경우 true, 그렇지 않으면 false.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


텍스트 추출을 활성화하거나 비활성화합니다.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 텍스트 추출을 활성화하려면 true, 비활성화하려면 false. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


출력 이미지의 너비를 픽셀 단위로 가져옵니다.

이 속성을 사용하여 출력 이미지 너비(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 \#setMaxWidth(int).setMaxWidth(int) 속성이 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 출력 이미지의 너비.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


출력 이미지의 너비(픽셀)를 설정합니다.

이 속성을 사용하여 출력 이미지 너비(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 \#setMaxWidth(int).setMaxWidth(int) 속성이 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 출력 이미지의 너비. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


출력 이미지의 높이(픽셀)를 가져옵니다.

이 속성을 사용하여 출력 이미지 높이(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 \#setMaxHeight(int).setMaxHeight(int) 속성이 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 출력 이미지의 높이.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


출력 이미지의 높이를 픽셀 단위로 설정합니다.

이 속성을 사용하여 출력 이미지 높이(픽셀 단위)를 설정합니다. 코드 예제는 [documentation][]을 참조하십시오. 이 속성을 설정하면 \#setMaxHeight(int).setMaxHeight(int) 속성이 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 출력 이미지의 높이. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


출력 페이지 스트림을 생성 및 해제하는 메서드를 구현하는 팩토리를 가져옵니다.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words 또는 Email 문서의 저장 진행 상황을 추정하기 위한 콜백을 가져옵니다.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 문서 저장 진행 상황을 추정하는 콜백입니다.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words 또는 Email 문서의 저장 진행 상황을 추정하기 위한 콜백을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 문서 저장 진행 상황을 추정하는 콜백입니다. |

