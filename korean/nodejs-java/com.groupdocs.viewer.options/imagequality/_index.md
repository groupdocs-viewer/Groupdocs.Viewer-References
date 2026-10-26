---
title: "ImageQuality"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "PDF 문서에 포함된 출력 HTML의 이미지 품질입니다."
type: docs
weight: 41
url: /ko/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

PDF 문서에 포함된 출력 HTML의 이미지 품질입니다.

ImageQuality 열거형은 GroupDocs.Viewer 구성 요소의 PDF 문서에 포함된 출력 HTML에서 이미지의 품질을 나타냅니다. 생성된 HTML 출력에서 이미지 렌더링 및 압축을 제어하는 데 사용할 수 있는 다양한 이미지 품질 수준을 제공합니다.

예시 사용법:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [LOW](#LOW) | 허용 가능한 품질과 최고의 성능. |
| [MEDIUM](#MEDIUM) | 더 나은 품질과 느린 성능. |
| [HIGH](#HIGH) | 최고 품질이지만 느린 성능. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


허용 가능한 품질과 최고의 성능. 이 설정은 이미지 품질보다 렌더링 속도를 우선시합니다.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


더 나은 품질과 느린 성능. 이 설정은 이미지 품질과 렌더링 속도 사이의 균형을 제공합니다.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


최고 품질이지만 느린 성능. 이 설정은 렌더링 속도보다 이미지 품질을 우선시합니다.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
