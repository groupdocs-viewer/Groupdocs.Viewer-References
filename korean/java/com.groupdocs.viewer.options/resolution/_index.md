---
title: "Resolution"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "이미지 출력 문서의 해상도를 설정하는 옵션을 제공합니다."
type: docs
weight: 44
url: /ko/java/com.groupdocs.viewer.options/resolution/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Resolution extends Enum<Resolution>
```

이미지 해상도를 설정하는 옵션을 제공합니다 : 출력 문서.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [DPI_330](#DPI-330) | 고해상도(HD) 디스플레이에 적합한 좋은 품질. |
|
|  | [DPI_220](#DPI-220) | 대부분의 프린터와 화면에서 뛰어난 품질. |
|
|  | [DPI_150](#DPI-150) | 웹 페이지와 프로젝터에 적합합니다. |
|
|  | [DPI_96](#DPI-96) | 웹 페이지와 프로젝터에 적합합니다. |
|
|  | [DPI_72](#DPI-72) | 기본 압축 수준. |
|
|  | [DOCUMENT_RESOLUTION](#DOCUMENT-RESOLUTION) | 기본 압축 수준 - 문서와 동일하게. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getValue()](#getValue--) | 품질 DPI. |
|
|  | [getSlidesPicturesResolution()](#getSlidesPicturesResolution--) | 옵션 Resolution 클래스에서 Aspose.Slides 이미지 해상도를 가져옵니다. |
|
### DPI_330 {#DPI-330}
```
public static final Resolution DPI_330
```


고해상도(HD) 디스플레이에 적합한 좋은 품질.


### DPI_220 {#DPI-220}
```
public static final Resolution DPI_220
```


대부분의 프린터와 화면에서 뛰어난 품질.


### DPI_150 {#DPI-150}
```
public static final Resolution DPI_150
```


웹 페이지와 프로젝터에 적합합니다.


### DPI_96 {#DPI-96}
```
public static final Resolution DPI_96
```


웹 페이지와 프로젝터에 적합합니다.


### DPI_72 {#DPI-72}
```
public static final Resolution DPI_72
```


기본 압축 수준.


### DOCUMENT_RESOLUTION {#DOCUMENT-RESOLUTION}
```
public static final Resolution DOCUMENT_RESOLUTION
```


기본 압축 수준 - 문서와 동일하게.


### values() {#values--}
```
public static Resolution[] values()
```




**Returns:**
com.groupdocs.viewer.options.Resolution[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Resolution valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
com.groupdocs.viewer.options.Resolution
### getValue() {#getValue--}
```
public int getValue()
```


품질 DPI.


**Returns:**
int
### getSlidesPicturesResolution() {#getSlidesPicturesResolution--}
```
public int getSlidesPicturesResolution()
```


옵션 Resolution 클래스에서 Aspose.Slides 이미지 해상도를 가져옵니다.


**Returns:**
int
