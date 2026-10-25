---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer 인스턴스에 로드된 PDF 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Viewer 인스턴스로 로드된 PDF 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다.


이 글꼴은 문서 내용에 사용되며 다음 중 하나입니다:

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF 글꼴 추출에 사용되는 내부 생성자입니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 글꼴 패밀리 이름을 가져옵니다. |
|
|  | [getStyle()](#getStyle--) | 이 글꼴의 스타일을 가져옵니다. |
|
|  | [isEmbedded()](#isEmbedded--) | 글꼴이 PDF 문서에 포함되어 있는지 여부를 반환합니다. |
|
|  | [isInstalled()](#isInstalled--) | 글꼴이 운영 체제에 설치되어 있는지 여부를 반환합니다. |
|
|  | [getFormat()](#getFormat--) | 글꼴의 파일 형식을 반환합니다. |
|
|  | [getContent()](#getContent--) | 글꼴의 바이너리 내용을 반환합니다. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | CSS @font-face 규칙으로 이 글꼴을 직렬화합니다. |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF 글꼴 추출에 사용되는 내부 생성자입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | familyName | java.lang.String | 글꼴 패밀리 이름 |
|
|  | style | com.groupdocs.viewer.fonts.FontStyles | 스타일 (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | PDF에 글꼴이 포함된 경우 true |
|
|  | isInstalled | boolean | OS에 글꼴이 설치된 경우 true |
|
|  | content | byte[] | 바이너리 글꼴 데이터 (nullable) |
|
|  | 형식 | int | 글꼴 파일 형식 |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


글꼴 패밀리 이름을 가져옵니다.


**Returns:**
java.lang.String - 패밀리 이름 문자열 (null이 아니고 비어 있지 않음)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


이 글꼴의 스타일을 가져옵니다.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - 글꼴 스타일

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


글꼴이 PDF 문서에 포함되어 있는지 여부를 반환합니다.


**Returns:**
boolean - 포함된 경우 true

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


글꼴이 운영 체제에 설치되어 있는지 여부를 반환합니다.


**Returns:**
boolean - 설치된 경우 true

### getFormat() {#getFormat--}
```
public int getFormat()
```


글꼴의 파일 형식을 반환합니다.


**Returns:**
int - 글꼴 형식 열거형

### getContent() {#getContent--}
```
public byte[] getContent()
```


글꼴의 바이너리 내용을 반환합니다.


**Returns:**
byte[] - 바이트 배열 또는 사용 불가능한 경우 null

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


CSS @font-face 규칙으로 이 글꼴을 직렬화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | output | java.io.Writer | CSS가 기록될 writer |
|

