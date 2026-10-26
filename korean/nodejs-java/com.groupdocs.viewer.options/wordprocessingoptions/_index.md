---
title: "WordProcessingOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 38
url: /ko/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다.

WordProcessingOptions 클래스는 GroupDocs.Viewer 구성 요소에서 워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다. 이 클래스는 워드 프로세싱 파일의 렌더링 프로세스와 출력 형식을 제어할 수 있는 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 [documentation][]을 참조하십시오.

예시 사용법:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | WordProcessingOptions 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageSize()](#getPageSize--) | HTM 및 HTML 파일 렌더링을 위한 페이지 크기를 가져옵니다. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM 및 HTML 파일 렌더링을 위한 페이지 크기를 설정합니다. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | 추적된 변경(리비전) 렌더링이 활성화되어 있는지 표시합니다. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | 추적된 변경(리비전) 렌더링을 활성화할지 설정합니다. |
| [getLeftMargin()](#getLeftMargin--) | HTML 렌더링을 위한 왼쪽 페이지 여백을 가져옵니다. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML 렌더링을 위한 왼쪽 페이지 여백을 설정합니다. |
| [getRightMargin()](#getRightMargin--) | HTML 렌더링을 위한 오른쪽 페이지 여백을 가져옵니다. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML 렌더링을 위한 오른쪽 페이지 여백을 설정합니다. |
| [getTopMargin()](#getTopMargin--) | HTML 렌더링을 위한 상단 페이지 여백을 가져옵니다. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML 렌더링을 위한 상단 페이지 여백을 설정합니다. |
| [getBottomMargin()](#getBottomMargin--) | 하단 페이지 여백 (HTML 렌더링 전용) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML 렌더링을 위한 하단 페이지 여백을 설정합니다. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | 이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | 이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화해야 하는지 여부를 나타냅니다. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화할지 여부를 설정합니다. |
| [isUpdateFields()](#isUpdateFields--) | 입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트해야 하는지 여부를 결정하는 값을 가져옵니다. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트해야 하는지 여부를 결정하는 값을 설정합니다. |
| [equals(Object o)](#equals-java.lang.Object-) | 옵션이 변경되었는지 확인합니다. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


WordProcessingOptions 클래스의 새 인스턴스를 초기화합니다. 워드 프로세싱 문서 렌더링 옵션을 포함합니다. 자세한 내용은 [documentation][].을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM 및 HTML 파일 렌더링을 위한 페이지 크기를 가져옵니다.

기본 페이지 크기를 사용할 경우 일부 콘텐츠가 페이지 프레임에 맞지 않을 수 있습니다. 내용을 맞추려면 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3)와 같이 더 큰 페이지 크기(A3 등)를 설정할 수 있습니다.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM 및 HTML 파일 렌더링을 위한 페이지 크기를 설정합니다.

기본 페이지 크기를 사용할 경우 일부 콘텐츠가 페이지 프레임에 맞지 않을 수 있습니다. 내용을 맞추려면 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3)와 같이 더 큰 페이지 크기(A3 등)를 설정할 수 있습니다.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 출력 페이지의 크기입니다. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


추적된 변경(리비전) 렌더링이 활성화되어 있는지 표시합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean - 추적된 변경 사항 렌더링이 활성화된 경우 true, 그렇지 않으면 false.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


추적된 변경(리비전) 렌더링을 활성화할지 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | 추적된 변경 사항 렌더링을 활성화하려면 true, 비활성화하려면 false. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML 렌더링을 위한 왼쪽 페이지 여백을 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 왼쪽 페이지 여백 값.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML 렌더링을 위한 왼쪽 페이지 여백을 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| leftMargin | java.lang.Double | 설정할 왼쪽 페이지 여백 값입니다. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML 렌더링을 위한 오른쪽 페이지 여백을 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 오른쪽 페이지 여백 값.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML 렌더링을 위한 오른쪽 페이지 여백을 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rightMargin | java.lang.Double | 설정할 오른쪽 페이지 여백 값입니다. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML 렌더링을 위한 상단 페이지 여백을 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 상단 페이지 여백.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML 렌더링을 위한 상단 페이지 여백을 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| topMargin | java.lang.Double | 설정할 상단 페이지 여백입니다. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


하단 페이지 여백 (HTML 렌더링 전용)

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 하단 페이지 여백.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML 렌더링을 위한 하단 페이지 여백을 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bottomMargin | java.lang.Double | 설정할 하단 페이지 여백입니다. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다.

**Returns:**
boolean - OpenType 기능이 활성화된 경우 True, 그렇지 않으면 false.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | OpenType 기능을 활성화하려면 true, 그렇지 않으면 false. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화할지 여부를 나타냅니다. 이 옵션을 true로 설정하면 HTML 렌더링 시 목차의 상대 링크가 span 태그로 대체되어 기능은 제거되지만 시각적 모양은 유지됩니다. PDF 렌더링에서는 목차가 링크 없이 일반 텍스트로 렌더링됩니다.

**Returns:**
boolean - 목차 탐색이 비활성화된 경우 true; 그렇지 않으면 false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화할지 여부를 설정합니다. 이 옵션을 true로 설정하면 HTML 렌더링 시 목차의 상대 링크가 span 태그로 대체되어 기능은 제거되지만 시각적 모양은 유지됩니다. PDF 렌더링에서는 목차가 링크 없이 일반 텍스트로 렌더링됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| unlinkTableOfContents | boolean | 목차 탐색을 비활성화할지 여부를 나타냅니다. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트할지 여부를 결정하는 값을 가져옵니다. 이 속성의 기본값은 true \u2014 저장하기 전에 필드가 업데이트됩니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트할지 여부를 결정하는 값을 설정합니다. 이 속성의 기본값은 true \u2014 저장하기 전에 필드가 업데이트됩니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


옵션이 변경되었는지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| o | java.lang.Object | 동등성을 비교할 객체. |

**Returns:**
boolean - 옵션이 지정된 객체와 동일하면 true, 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 객체에 대한 해시 코드 값을 계산합니다. 해시 코드는 객체의 내부 상태를 기반으로 하며 해시 맵 및 해시 집합과 같은 해시 기반 데이터 구조에서 사용됩니다.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - 이 객체에 대한 해시 코드 값.
