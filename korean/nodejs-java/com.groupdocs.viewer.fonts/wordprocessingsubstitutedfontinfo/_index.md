---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "GroupDocs.Viewer를 통해 WordProcessing 문서에서 사용되는 대체 글꼴 하나의 메타데이터와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 18
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

GroupDocs.Viewer를 통해 WordProcessing 문서에서 사용되는 대체 폰트 하나의 메타데이터와 바이너리 데이터를 캡슐화합니다. 불변 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | 모든 필드를 초기화하는 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 대체 폰트의 패밀리 이름을 반환합니다 (null이 아님). |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | 원본 폰트의 패밀리 이름을 반환합니다 (null이 아님). |
| [getStyle()](#getStyle--) | 원본 폰트의 스타일을 반환합니다. |
| [getContent()](#getContent--) | 대체 폰트의 바이너리 내용을 반환합니다 (null이 아님). |
| [getFormat()](#getFormat--) | 대체 폰트의 폰트 형식을 반환합니다. |
| [toString()](#toString--) | 이 대체 폰트를 설명하는 문자열을 반환합니다: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | 원본 패밀리, 대체 패밀리 및 스타일을 기준으로 한 동등성. |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 유틸리티 메서드를 사용하여 이 폰트를 @font-face CSS 규칙으로 직렬화합니다. |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


모든 필드를 초기화하는 생성자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| originalFamilyName | java.lang.String | 원본 폰트 이름 (시스템에 없음) |
| substitutedFamilyName | java.lang.String | 대체된 글꼴 이름 (사용 가능) |
| 스타일 | com.groupdocs.viewer.fonts.FontStyles | 글꼴 스타일 (Regular, Bold, Italic, BoldItalic) |
| 내용 | byte[] | 대체된 글꼴의 바이너리 내용 (절대 null이 아님) |
| 형식 | int | 글꼴 형식 (TrueType, OpenType 등) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


대체 폰트의 패밀리 이름을 반환합니다 (null이 아님).

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


원본 폰트의 패밀리 이름을 반환합니다 (null이 아님).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


원본 폰트의 스타일을 반환합니다.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


대체 폰트의 바이너리 내용을 반환합니다 (null이 아님).

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


대체 폰트의 폰트 형식을 반환합니다.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


이 대체 폰트를 설명하는 문자열을 반환합니다: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


원본 패밀리, 대체 패밀리 및 스타일을 기반으로 한 동등성. C\# IEqualityComparer와 같은 HashSet 또는 HashMap에서 사용하려면 필요합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


유틸리티 메서드를 사용하여 이 폰트를 @font-face CSS 규칙으로 직렬화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 출력 | java.io.Writer |  |

