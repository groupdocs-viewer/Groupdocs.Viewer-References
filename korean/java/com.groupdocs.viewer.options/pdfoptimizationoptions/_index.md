---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "이 클래스를 사용하여 출력 PDF 파일에 적용할 PDF 최적화 옵션을 지정합니다."
type: docs
weight: 21
url: /ko/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

이 클래스를 사용하여 출력 PDF 파일에 적용할 PDF 최적화 옵션을 지정합니다.


이러한 최적화 옵션은 PDF로 내보내기가 지원되는 모든 입력 파일 형식에 대해 지원됩니다.
자세한 내용과 코드 샘플은 이 [페이지](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) 및 해당 하위 페이지를 참조하십시오.


사용 예시:

````

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | MaxResolution 옵션의 기본값을 300으로, ImageQuality 옵션의 기본값을 100으로 설정합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | 웹 브라우저를 통한 온라인 보기용으로 출력 PDF 파일 최적화를 활성화합니다. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | 웹 브라우저를 통한 온라인 브라우징을 위해 출력 PDF를 최적화할지 여부를 설정합니다. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | 주석이 불필요할 경우 삭제할 수 있습니다. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | PDF에서 불필요한 주석을 제거할지 여부를 설정합니다. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | PDF 문서에 AcroForms가 포함된 경우, 양식 필드를 평탄화하여 파일 크기를 줄일 수 있습니다. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | PDF에서 양식 필드를 제거할지 여부를 설정합니다. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF 파일은 텍스트, 이미지, 첨부 파일, 주석, 그래프 및 기타 객체로 구성됩니다. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | PDF를 그레이스케일로 변환할지 여부를 설정합니다. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | 페이지에 텍스트를 표시하는 데 사용되는 모든 글꼴은 글자 문자에 대한 글리프 집합을 포함합니다. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | PDF에서 글꼴을 서브셋할지 여부를 설정합니다. |
|
|  | [isCompressImages()](#isCompressImages--) | 원본 PDF 파일에 이미지가 포함된 경우, 이미지를 압축하고 품질을 설정하는 것을 고려하십시오. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | PDF에서 이미지를 압축할지 여부를 설정합니다. |
|
|  | [getImageQuality()](#getImageQuality--) | 원본 PDF 파일에 이미지가 포함된 경우, 이미지를 압축하고 품질을 설정하는 것을 고려하십시오. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | PDF에서 이미지를 압축할 때 이미지 품질을 설정합니다. |
|
|  | [isResizeImages()](#isResizeImages--) | CompressImages 옵션과 함께 사용하여 낮은 해상도로 이미지를 크기 조정할 수 있습니다. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | PDF의 이미지 크기를 조정할지 여부를 설정합니다. |
|
|  | [getMaxResolution()](#getMaxResolution--) | CompressImages 옵션과 함께 사용하여 낮은 해상도로 이미지를 크기 조정할 수 있습니다. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | PDF의 이미지 크기를 조정하기 위한 최대 해상도를 설정합니다. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Excel 스프레드시트의 테두리 선과 글꼴을 최적화하여 출력 파일 크기를 줄입니다. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | PDF 내 스프레드시트를 최적화할지 여부를 설정합니다. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | true로 설정된 경우 개인 정보(페이지 조각 정보)를 제거합니다. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | PDF에서 개인 정보를 제거할지 여부를 설정합니다. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | 문서가 포함된 글꼴을 사용하는 경우, 모든 글꼴 데이터가 문서에 포함된다는 의미입니다. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | PDF에 포함된 글꼴을 포함 해제할지 여부를 설정합니다. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | 때때로 문서에 여러 개의 동일한 리소스 스트림(예: 이미지)이 포함될 수 있습니다. |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | PDF에서 중복 스트림을 연결할지 여부를 설정합니다. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | 이 속성을 true로 설정하면, 동일한 페이지에 대해 문서를 최적화할 때 페이지 콘텐츠가 재사용됩니다. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | PDF에서 페이지 콘텐츠 재사용을 허용할지 여부를 설정합니다. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | 때때로 문서에 사용되지 않은 리소스 스트림이 포함됩니다. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | PDF에서 사용되지 않은 스트림을 제거할지 여부를 설정합니다. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF 문서에 때때로 참조되지 않은 PDF 객체가 포함될 수 있습니다 |
문서의 다른 객체에서.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | PDF에서 사용되지 않은 객체를 제거할지 여부를 설정합니다. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


MaxResolution 옵션의 기본값을 300으로, ImageQuality 옵션의 기본값을 100으로 설정합니다.


자세한 내용과 코드 샘플은 이 [페이지](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) 및 해당 하위 페이지를 참조하십시오.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


웹 브라우저를 통한 온라인 보기용으로 출력 PDF 파일 최적화를 활성화합니다.


코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)를 참조하십시오.


**Returns:**
boolean -  true  출력 PDF가 온라인 브라우징에 최적화된 경우,  false  그 외의 경우.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


웹 브라우저를 통한 온라인 브라우징을 위해 출력 PDF를 최적화할지 여부를 설정합니다.


코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | linearize | boolean | true  출력 PDF를 온라인 브라우징에 최적화하려면,  false  그 외의 경우. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


주석은 불필요할 때 삭제할 수 있습니다. 필요하지만 추가 편집이 필요하지 않을 경우 평탄화할 수 있습니다. 이렇게 하면 파일 크기가 줄어듭니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)를 참조하십시오.


**Returns:**
boolean -  true  주석이 제거된 경우,  false  그 외의 경우.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


PDF에서 불필요한 주석을 제거할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  불필요한 주석을 제거하려면,  false  그렇지 않은 경우. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


PDF 문서에 AcroForms가 포함된 경우, 양식 필드를 평탄화하여 파일 크기를 줄일 수 있습니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)를 참조하십시오.


**Returns:**
boolean -  true  폼 필드가 제거된 경우,  false  그렇지 않은 경우.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


PDF에서 양식 필드를 제거할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | removeFormFields | boolean | true  폼 필드를 제거하려면,  false  그렇지 않은 경우. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF 파일은 텍스트, 이미지, 첨부 파일, 주석, 그래프 및 기타 객체로 구성됩니다.
PDF를 RGB 색공간에서 회색조로 변환해야 하는 요구 사항이 발생할 수 있습니다. 이렇게 하면 해당 PDF 파일을 인쇄할 때 더 빠르게 처리됩니다.
또한 파일을 회색조로 변환하면 문서 크기도 감소하지만, 이로 인해 문서 품질이 떨어질 수 있습니다.
현재 이 기능은 Adobe Acrobat의 Pre-Flight 기능에서 지원됩니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)를 참조하십시오.


**Returns:**
boolean -  true  PDF가 회색조로 변환된 경우,  false  그렇지 않은 경우.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


PDF를 그레이스케일로 변환할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  PDF를 회색조로 변환하려면,  false  그렇지 않은 경우. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


페이지에 텍스트를 표시하는 데 사용되는 모든 글꼴은 글자 문자에 대한 글리프 집합을 포함합니다.
PDF 사양은 "폰트 서브셋"을 지원합니다. 즉, 사용된 글리프만 포함된 폰트입니다.
텍스트를 업데이트해야 할 때(필요한 글리프가 폰트에 없을 수 있기 때문에) 문제가 발생할 수 있지만, 변경될 계획이 없는 문서의 경우 크기를 줄이는 데 도움이 됩니다.


***Note:** The default value is 
false
.*
파일에 임베디드 폰트가 사용된 경우 모든 폰트 데이터를 포함합니다. GroupDocs.Viewer는 임베디드 폰트를 서브셋하여 파일 크기를 줄일 수 있습니다. 코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)를 참조하십시오.


**Returns:**
boolean -  true  폰트가 서브셋된 경우,  false  그렇지 않은 경우.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


PDF에서 글꼴을 서브셋할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
파일에 임베디드 폰트가 사용된 경우 모든 폰트 데이터를 포함합니다. GroupDocs.Viewer는 임베디드 폰트를 서브셋하여 파일 크기를 줄일 수 있습니다. 코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | subsetFonts | boolean | true  폰트를 서브셋하려면,  false  그렇지 않은 경우. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


원본 PDF 파일에 이미지가 포함된 경우, 이미지를 압축하고 품질을 설정하는 것을 고려하십시오.
이미지 압축을 활성화하려면 이 옵션을 true로 설정하십시오. 문서의 모든 이미지가 다시 압축됩니다.
압축은 ImageQuality 속성으로 정의되며, 이는 품질을 백분율로 나타낸 값입니다.
100%는 품질이 변하지 않음을 의미합니다. 이미지 품질을 낮추려면 ImageQuality 속성을 100 이하로 설정하십시오.


***Note:** The default value is 
false
.*
이 옵션을 사용하면 다른 압축 옵션을 허용할 수 있습니다: #setImageQuality(int).setImageQuality(int) 및 . 코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)를 참조하십시오.


**Returns:**
boolean -  true  이미지가 압축된 경우,  false  그렇지 않은 경우.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


PDF에서 이미지를 압축할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
이 옵션을 사용하면 다른 압축 옵션을 허용할 수 있습니다: #setImageQuality(int).setImageQuality(int) 및 . 코드 예제는 이 [문서](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | compressImages | boolean | true  이미지를 압축하려면,  false  그렇지 않은 경우. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


소스 PDF 파일에 이미지가 포함된 경우, 이미지를 압축하고 품질을 설정하는 것을 고려하십시오. 이미지 압축을 활성화하려면 CompressImages 옵션을 true로 설정하십시오. 문서의 모든 이미지가 다시 압축됩니다. 압축은 ImageQuality 속성으로 정의되며, 이는 품질을 백분율로 나타낸 값입니다. 100%는 품질이 변경되지 않음을 의미합니다. 이미지 품질을 낮추려면 CompressImages 옵션을 true로 설정하고 ImageQuality 속성을 100 이하로 설정하십시오.

<br />


***Note:** The default value is 
100
.*
이미지 품질을 변경하려면 먼저 #setCompressImages(boolean).setCompressImages(boolean) 속성을 true로 설정하십시오. 코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)를 참조하십시오.


**Returns:**
int - 이미지 품질 (값은 1에서 100 사이).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


PDF에서 이미지를 압축할 때 이미지 품질을 설정합니다.


***Note:** The default value is 
100
.*
이미지 품질을 변경하려면 먼저 #setCompressImages(boolean).setCompressImages(boolean) 속성을 true로 설정하십시오. 코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageQuality | int | 이미지 품질 (값은 1에서 100 사이). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


CompressImages 옵션과 함께 사용하여 낮은 해상도로 이미지를 크기 조정할 수 있습니다.
이 경우 CompressImage를 true로, ResizeImages를 true로, MaxResolution을 적절한 값으로 설정해야 합니다.


***Note:** The default value is 
false
.*
이 옵션을 허용하려면 속성을 true로 설정하십시오. 이 옵션은 속성을 설정할 수 있게 합니다. 코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)를 참조하십시오.


**Returns:**
boolean -  true  이미지가 크기 조정된 경우,  false  그렇지 않은 경우.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


PDF의 이미지 크기를 조정할지 여부를 설정합니다.


***Note:** The default value is 
false
.*
이 옵션을 허용하려면 속성을 true로 설정하십시오. 이 옵션은 속성을 설정할 수 있게 합니다. 코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | resizeImages | boolean | true  이미지를 크기 조정하려면,  false  그렇지 않은 경우. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


CompressImages 옵션과 함께 사용하여 낮은 해상도로 이미지를 크기 조정할 수 있습니다. 이 경우 CompressImage를 true로, ResizeImages를 true로, MaxResolution을 적절한 값으로 설정해야 합니다.


***Note:** The default value is 
300
.*
이 옵션을 허용하려면 #setCompressImages(boolean).setCompressImages(boolean) 및 #setMaxResolution(int).setMaxResolution(int) 속성을 true로 설정하십시오.
코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)를 참조하십시오.


**Returns:**
int - 이미지의 최대 해상도.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


PDF의 이미지 크기를 조정하기 위한 최대 해상도를 설정합니다.


***Note:** The default value is 
300
.*
이 옵션을 허용하려면 #setCompressImages(boolean).setCompressImages(boolean) 및 #setMaxResolution(int).setMaxResolution(int) 속성을 true로 설정하십시오.
코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | maxResolution | int | 이미지의 최대 해상도. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Excel 스프레드시트의 테두리 선과 글꼴을 최적화하여 출력 파일 크기를 줄입니다.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)를 참조하십시오.


**Returns:**
boolean -  true  스프레드시트가 최적화된 경우,  false  그렇지 않은 경우.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


PDF 내 스프레드시트를 최적화할지 여부를 설정합니다.


코드 예제는 이 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  스프레드시트를 최적화하려면,  false  그렇지 않은 경우. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


true로 설정된 경우 개인 정보(페이지 조각 정보)를 제거합니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  개인 정보가 제거된 경우,  false  그렇지 않은 경우.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


PDF에서 개인 정보를 제거할지 여부를 설정합니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  개인 정보를 제거하려면,  false  그렇지 않은 경우. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


문서가 포함된 글꼴을 사용하는 경우, 모든 글꼴 데이터가 문서에 포함된다는 의미입니다.
장점은 폰트가 사용자\u2019의 머신에 설치되어 있든 없든 문서를 볼 수 있다는 것입니다. 그러나 폰트를 포함하면 문서 크기가 커집니다.
unembed fonts 메서드는 모든 포함된 폰트를 제거합니다. 이는 문서 크기를 감소시키지만 올바른 폰트가 설치되어 있지 않으면 문서를 읽을 수 없게 될 수 있습니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  포함된 폰트가 제거된 경우,  false  그 외의 경우.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


PDF에 포함된 글꼴을 포함 해제할지 여부를 설정합니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | unembedFonts | boolean | true  포함된 폰트를 제거하려면,  false  그 외의 경우. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


때때로 문서에 여러 개의 동일한 리소스 스트림(예: 이미지)이 포함될 수 있습니다.
예를 들어 문서를 자체와 연결할 때 이런 일이 발생할 수 있습니다.
출력 문서는 동일한 리소스 스트림의 두 개 독립적인 복사본을 포함합니다.
우리는 모든 리소스 스트림을 분석하고 비교합니다. 스트림이 중복될 경우 병합되어 하나의 복사본만 남고, 참조가 적절히 변경되며 객체의 복사본이 제거됩니다.
때때로 이는 문서 크기를 감소시킵니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  중복 스트림이 연결된 경우,  false  그 외의 경우.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


PDF에서 중복 스트림을 연결할지 여부를 설정합니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  중복 스트림을 연결하려면,  false  그 외의 경우. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


이 속성을 true로 설정하면, 동일한 페이지에 대해 문서를 최적화할 때 페이지 콘텐츠가 재사용됩니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  페이지 콘텐츠가 재사용되는 경우,  false  그 외의 경우.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


PDF에서 페이지 콘텐츠 재사용을 허용할지 여부를 설정합니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  페이지 콘텐츠 재사용을 허용하려면,  false  그 외의 경우. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


때때로 문서에 사용되지 않은 리소스 스트림이 포함됩니다.
이 스트림들은 페이지\u2019의 리소스 사전에서 참조되기 때문에 \u201cunused objects\u201d가 아닙니다.
이미지가 페이지에서 제거되었지만 페이지 리소스에서는 제거되지 않은 경우에 이런 일이 발생할 수 있습니다.
또한, 문서에서 페이지를 추출하고 문서 페이지가 \u201ccommon\u201d 리소스를 가지고 있을 때 이런 상황이 자주 발생합니다,
즉, 동일한 Resources 객체입니다. 페이지 콘텐츠는 리소스 스트림인지 여부를 판단하기 위해 분석됩니다
사용되는지 여부를 확인합니다. 사용되지 않는 스트림은 제거됩니다. 때때로 이는 문서 크기를 감소시킵니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  사용되지 않는 스트림이 제거된 경우,  false  그 외의 경우.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


PDF에서 사용되지 않은 스트림을 제거할지 여부를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  사용되지 않는 스트림을 제거하려면,  false  그 외의 경우. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDF 문서에 때때로 참조되지 않은 PDF 객체가 포함될 수 있습니다
문서의 다른 객체에서. 예를 들어 이런 일이 발생할 수 있습니다,
페이지가 문서 페이지 트리에서 제거되었지만 페이지 객체 자체는 isn\u2019t 제거됩니다.
이러한 객체를 제거해도 문서가 무효화되지는 않으며 오히려 크기가 줄어듭니다.


***Note:** The default value is 
false
.*


**Returns:**
boolean - 사용되지 않은 객체가 제거되면 true, 그렇지 않으면 false.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


PDF에서 사용되지 않은 객체를 제거할지 여부를 설정합니다.


***Note:** The default value is 
false
.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | 사용되지 않은 객체를 제거하려면 true, 그렇지 않으면 false. |
|

