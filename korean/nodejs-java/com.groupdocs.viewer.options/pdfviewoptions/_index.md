---
title: "PdfViewOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "문서를 PDF 형식으로 렌더링하는 옵션을 제공합니다."
type: docs
weight: 23
url: /ko/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

문서를 PDF 형식으로 렌더링하는 옵션을 제공합니다.

PdfViewOptions 클래스는 GroupDocs.Viewer 구성 요소에서 문서를 PDF 형식으로 렌더링하는 데 사용할 수 있는 추가 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 [documentation][].

예시 사용법:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | PdfViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | PdfViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | PdfViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PdfViewOptions()](#PdfViewOptions--) | PdfViewOptions 클래스를 기본 설정으로 새 인스턴스를 초기화합니다. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | PdfViewOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | PdfViewOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | 다양한 옵션을 사용한 최적화 기술을 적용하여 출력 PDF 파일 크기를 줄입니다. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | 다양한 옵션을 사용한 최적화 기술을 적용하여 출력 PDF 파일 크기를 줄입니다. |
| [getImageMaxWidth()](#getImageMaxWidth--) | 출력 이미지의 최대 너비(픽셀)를 가져옵니다. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 출력 이미지의 최대 너비(픽셀)를 설정합니다. |
| [getImageMaxHeight()](#getImageMaxHeight--) | 출력 이미지의 최대 높이(픽셀)를 가져옵니다. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 출력 이미지의 최대 높이(픽셀)를 설정합니다. |
| [getImageWidth()](#getImageWidth--) | 출력 이미지의 너비(픽셀)를 가져옵니다. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | 출력 이미지의 너비(픽셀)를 설정합니다. |
| [getImageHeight()](#getImageHeight--) | 출력 이미지의 높이를 픽셀 단위로 가져옵니다. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | 출력 이미지의 높이를 픽셀 단위로 설정합니다. |
| [getSecurity()](#getSecurity--) | 출력 PDF 문서에 대한 보안 옵션을 가져옵니다. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | 출력 PDF 문서에 대한 보안 옵션을 설정합니다. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words 또는 Email 문서를 저장하는 진행 상황을 추정하는 데 사용되는 콜백을 가져옵니다. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words 또는 Email 문서를 저장하는 진행 상황을 추정하는 데 사용되는 콜백을 설정합니다. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


PdfViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


PdfViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | 출력 파일 데이터를 쓰기 위해 스트림을 인스턴스화하는 데 사용되는 메서드입니다. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | createFileStream 메서드에 의해 생성된 스트림을 해제하는 데 사용되는 메서드입니다. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


PdfViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | 출력 파일 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리입니다. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


PdfViewOptions 클래스를 기본 설정으로 새 인스턴스를 초기화합니다.

이 생성자는 출력 파일의 파일 경로 형식으로 "output.pdf"를 사용하여 새로운 PdfViewOptions 객체를 생성합니다. 출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


PdfViewOptions 클래스의 새 인스턴스를 초기화합니다.

이 생성자는 지정된 outputFilePath 매개변수를 사용하여 출력 PDF 파일의 경로를 나타내는 새로운 PdfViewOptions 객체를 생성합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFilePath | java.lang.String | 출력 PDF 파일의 경로입니다. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


PdfViewOptions 클래스의 새 인스턴스를 초기화합니다.

코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | 출력 PDF 파일의 경로입니다. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


다양한 옵션을 사용한 최적화 기술을 적용하여 출력 PDF 파일 크기를 줄입니다.

이 옵션은 PDF로 변환이 지원되는 모든 입력 파일 형식에 대해 지원됩니다: [Supported document formats][] 자세한 내용 및 코드 샘플은 이 [page][] 및 하위 페이지를 참조하십시오.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


다양한 옵션을 사용한 최적화 기술을 적용하여 출력 PDF 파일 크기를 줄입니다.

이 옵션은 PDF로 변환이 지원되는 모든 입력 파일 형식에 대해 지원됩니다: [Supported document formats][] 자세한 내용 및 코드 샘플은 이 [page][] 및 하위 페이지를 참조하십시오.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions 객체 또는 null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


출력 이미지의 최대 너비를 픽셀 단위로 가져옵니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 최대 출력 이미지 너비(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 PDF로 렌더링할 때 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 출력 이미지의 최대 너비(픽셀).
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


출력 이미지의 최대 너비를 픽셀 단위로 설정합니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 최대 출력 이미지 너비(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 PDF로 렌더링할 때 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageMaxWidth | int | 출력 이미지의 최대 너비(픽셀). |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


출력 이미지의 최대 높이를 픽셀 단위로 가져옵니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 최대 출력 이미지 높이(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 PDF로 렌더링할 때 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 출력 이미지의 최대 높이(픽셀).
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


출력 이미지의 최대 높이를 픽셀 단위로 설정합니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 최대 출력 이미지 높이(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 HTML로 렌더링할 때만 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 속성을 설정하면 이 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageMaxHeight | int | 출력 이미지의 최대 높이(픽셀)입니다. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


출력 이미지의 너비를 픽셀 단위로 가져옵니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 출력 이미지 너비(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 PDF로 렌더링할 때 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 출력 이미지의 너비(픽셀)입니다.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


출력 이미지의 너비를 픽셀 단위로 설정합니다. 이 매개변수는 단일 이미지 PDF를 변환할 때만 적용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageWidth | int | 출력 이미지의 너비(픽셀)입니다. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


출력 이미지의 높이를 픽셀 단위로 가져옵니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 출력 이미지 높이(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 HTML로 렌더링할 때만 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 출력 이미지의 높이(픽셀)입니다.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


출력 이미지의 높이를 픽셀 단위로 설정합니다. 이 매개변수는 단일 이미지를 HTML로 변환할 때만 적용됩니다.

이 속성을 사용하여 출력 이미지 높이(픽셀)를 설정합니다. GroupDocs.Viewer는 단일 이미지를 HTML로 렌더링할 때만 이 속성을 적용합니다. 자세한 내용은 [documentation][]을 참조하십시오. 이 속성을 설정하면 해당 속성은 무시됩니다.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageHeight | int | 출력 이미지의 높이(픽셀)입니다. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


출력 PDF 문서에 대한 보안 옵션을 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


출력 PDF 문서에 대한 보안 옵션을 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | 출력 PDF 문서에 대한 보안 옵션입니다. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words 또는 Email 문서를 저장하는 진행 상황을 추정하는 데 사용되는 콜백을 가져옵니다.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 문서 저장 진행 상황을 추정하는 콜백입니다.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words 또는 Email 문서를 저장하는 진행 상황을 추정하는 데 사용되는 콜백을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 문서 저장 진행 상황을 추정하는 콜백입니다. |

