---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 38
url: /ko/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다.


WordProcessingOptions 클래스는 워드 프로세싱 문서를 렌더링하기 위한 옵션을 제공합니다.
GroupDocs.Viewer 구성 요소에서. 사용될 수 있는 설정 및 매개변수를 캡슐화합니다.
워드 프로세싱 파일의 렌더링 프로세스와 출력 형식을 제어합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/)을 참조하십시오.


사용 예시:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | 새 인스턴스를 초기화합니다. |
WordProcessingOptions
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | HTM 및 HTML 파일을 렌더링하기 위한 페이지 크기를 가져옵니다. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM 및 HTML 파일을 렌더링하기 위한 페이지 크기를 설정합니다. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | 추적된 변경(수정) 렌더링이 활성화되어 있는지 여부를 나타냅니다. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | 추적된 변경(수정) 렌더링을 활성화할지 여부를 설정합니다. |
|
|  | [getLeftMargin()](#getLeftMargin--) | HTML 렌더링을 위한 왼쪽 페이지 여백을 가져옵니다. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML 렌더링을 위한 왼쪽 페이지 여백을 설정합니다. |
|
|  | [getRightMargin()](#getRightMargin--) | HTML 렌더링을 위한 오른쪽 페이지 여백을 가져옵니다. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML 렌더링을 위한 오른쪽 페이지 여백을 설정합니다. |
|
|  | [getTopMargin()](#getTopMargin--) | HTML 렌더링을 위한 상단 페이지 여백을 가져옵니다. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML 렌더링을 위한 상단 페이지 여백을 설정합니다. |
|
|  | [getBottomMargin()](#getBottomMargin--) | 하단 페이지 여백 (HTML 렌더링 전용) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML 렌더링을 위한 하단 페이지 여백을 설정합니다. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | 이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | 이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화해야 하는지 여부를 나타냅니다. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화할지 여부를 설정합니다. |
|
|  | [isUpdateFields()](#isUpdateFields--) | 입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트해야 하는지 여부를 결정하는 값을 가져옵니다. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트해야 하는지 여부를 결정하는 값을 설정합니다. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 생성된 이미지의 가로 해상도를 인치당 도트(dpi) 단위로 가져옵니다. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 생성된 이미지의 수평 해상도를 인치당 도트(dpi) 단위로 설정합니다. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 생성된 이미지의 세로 해상도를 인치당 도트(dpi) 단위로 가져옵니다. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 생성된 이미지의 수직 해상도를 인치당 도트(dpi) 단위로 설정합니다. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | 로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할 수 있게 합니다. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | 로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할 수 있게 합니다. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | 옵션이 변경되었는지 확인합니다. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


새 인스턴스를 초기화합니다.
WordProcessingOptions
클래스.
워드 프로세싱 문서를 렌더링하기 위한 옵션을 포함합니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) 를 참조하세요.


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM 및 HTML 파일을 렌더링하기 위한 페이지 크기를 가져옵니다.


기본 페이지 크기를 사용할 경우 일부 콘텐츠가 페이지 프레임에 맞지 않을 수 있습니다.
내용을 맞추려면 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) 와 같이 더 큰 페이지 크기(A3 등)를 설정할 수 있습니다.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM 및 HTML 파일을 렌더링하기 위한 페이지 크기를 설정합니다.


기본 페이지 크기를 사용할 경우 일부 콘텐츠가 페이지 프레임에 맞지 않을 수 있습니다.
내용을 맞추려면 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) 와 같이 더 큰 페이지 크기(A3 등)를 설정할 수 있습니다.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 출력 페이지의 크기입니다. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


추적된 변경(수정) 렌더링이 활성화되어 있는지 여부를 나타냅니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) 를 참조하세요.


**Returns:**
boolean -  true  트랙된 변경 사항 렌더링이 활성화된 경우,  false  그렇지 않은 경우.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


추적된 변경(수정) 렌더링을 활성화할지 여부를 설정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) 를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true  트랙된 변경 사항 렌더링을 활성화하려면,  false  비활성화하려면. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML 렌더링을 위한 왼쪽 페이지 여백을 가져옵니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Returns:**
java.lang.Double - 왼쪽 페이지 여백 값.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML 렌더링을 위한 왼쪽 페이지 여백을 설정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | 설정할 왼쪽 페이지 여백 값. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML 렌더링을 위한 오른쪽 페이지 여백을 가져옵니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Returns:**
java.lang.Double - 오른쪽 페이지 여백 값.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML 렌더링을 위한 오른쪽 페이지 여백을 설정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | 설정할 오른쪽 페이지 여백 값. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML 렌더링을 위한 상단 페이지 여백을 가져옵니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Returns:**
java.lang.Double - 위쪽 페이지 여백.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML 렌더링을 위한 상단 페이지 여백을 설정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | topMargin | java.lang.Double | 설정할 위쪽 페이지 여백. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


하단 페이지 여백 (HTML 렌더링 전용)
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Returns:**
java.lang.Double - 아래쪽 페이지 여백.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML 렌더링을 위한 하단 페이지 여백을 설정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) 를 참조하세요.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | 설정할 아래쪽 페이지 여백. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다.


**Returns:**
boolean - OpenType 기능이 활성화된 경우 true, 그렇지 않으면 false.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


이 옵션은 아랍어, 히브리어, 인도어 스크립트, 라틴 기반 또는 키릴 기반 스크립트를 렌더링할 때 커닝 및 기타 OpenType 기능을 활성화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | OpenType 기능을 활성화하려면 true, 그렇지 않으면 false. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화해야 하는지 여부를 나타냅니다. 이 옵션을 true로 설정하면 HTML 렌더링 시 목차의 상대 링크가 span 태그로 대체되어 기능은 제거되지만 시각적 모양은 유지됩니다. PDF 렌더링 시에는 목차가 링크 없이 일반 텍스트로 렌더링됩니다.


**Returns:**
boolean - 목차 탐색이 비활성화된 경우 true; 그렇지 않으면 false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML 또는 PDF로 렌더링할 때 목차 탐색을 비활성화할지 설정합니다. 이 옵션을 true로 설정하면 HTML 렌더링 시 목차의 상대 링크가 span 태그로 대체되어 기능은 제거되지만 시각적 모양은 유지됩니다. PDF 렌더링 시에는 목차가 링크 없이 일반 텍스트로 렌더링됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | 목차 탐색을 비활성화해야 하는지 여부를 나타냅니다. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트할지 여부를 결정하는 값을 가져옵니다. 이 속성의 기본값은 true \\u2014 저장하기 전에 필드가 업데이트됩니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)를 참조하십시오.


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


입력 WordProcessing 문서를 HTML, PDF, PNG 또는 JPEG 출력 형식으로 저장하기 전에 특정 유형의 필드를 업데이트할지 여부를 결정하는 값을 설정합니다. 이 속성의 기본값은 true \\u2014 저장하기 전에 필드가 업데이트됩니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


생성된 이미지의 수평 해상도를 인치당 도트(dpi) 단위로 가져옵니다. 이 옵션은 WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Returns:**
int - 인치당 도트(DPI) 단위의 수평 해상도.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


생성된 이미지의 수평 해상도를 인치당 도트(dpi) 단위로 설정합니다. 이 옵션은 WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | horizontalResolution | int | 인치당 도트(DPI) 단위의 수평 해상도. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


생성된 이미지의 수직 해상도를 인치당 도트(dpi) 단위로 가져옵니다. 이 옵션은 WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Returns:**
int - 인치당 도트(DPI) 단위의 수직 해상도.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


생성된 이미지의 수직 해상도를 인치당 도트(dpi) 단위로 설정합니다. 이 옵션은 WordProcessing 문서를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | verticalResolution | int | 인치당 도트(DPI) 단위의 수직 해상도. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할 수 있습니다. 기본값은 [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 문서는 그대로 유지됩니다.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


로드된 WordProcessing 문서에 페이지 번호를 강제로 적용할 수 있습니다. 기본값은 [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 문서는 그대로 유지됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | 페이지 번호 위치. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


옵션이 변경되었는지 확인합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | o | java.lang.Object | 동등성 비교를 위한 객체. |
|

**Returns:**
boolean - 옵션이 지정된 객체와 동일하면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 객체에 대한 해시 코드 값을 계산합니다. 해시 코드는 다음을 기반으로 합니다.
객체의 내부 상태이며 해시 기반 데이터 구조에서 사용됩니다
예: 해시 맵 및 해시 집합.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - 이 객체에 대한 해시 코드 값.

