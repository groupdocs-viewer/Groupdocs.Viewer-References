---
title: "WordProcessingFontInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Viewer 인스턴스에 로드된 WordProcessing 문서에서 하나의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 17
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Viewer 인스턴스에 로드된 WordProcessing 문서에서 하나의 글꼴에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서 내용에 사용되며 문서 자체에 포함되어 있거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치되어 있습니다.

불변 클래스입니다. 해당 인스턴스는 GroupDocs.Viewer 공개 API에 의해 생성 및 반환되며 일반적으로 사용자가 직접 생성해서는 안 됩니다. 자세한 내용은 문서를 참조하십시오: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 스타일이 없는 글꼴의 패밀리 이름으로, null이거나 비어 있지 않습니다. |
| [getAltFamilyName()](#getAltFamilyName--) | 글꼴의 대체 패밀리 이름. |
| [getStyle()](#getStyle--) | 글꼴 스타일 — Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다. |
| [isEmbedded()](#isEmbedded--) | 이 글꼴이 문서에 포함되어 있는지(true) 아니면 시스템 글꼴인지(false)를 나타냅니다. |
| [getFormat()](#getFormat--) | 이 글꼴의 형식. |
| [getContent()](#getContent--) | 이 글꼴의 내용을 바이트 배열로 제공하거나, 사용할 수 없을 경우 null입니다. |
| [getCharset()](#getCharset--) | 이 글꼴의 문자 집합. |
| [toString()](#toString--) | 다음 템플릿으로 이 글꼴에 대한 디버그 정보를 반환합니다: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 이 글꼴 정보를 @font-face CSS 규칙으로 직렬화하고 지정된 writer에 씁니다. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


스타일이 없는 글꼴의 패밀리 이름으로, null이거나 비어 있지 않습니다.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


글꼴의 대체 패밀리 이름. 없을 경우 빈 문자열을 반환합니다.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


글꼴 스타일 — Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


이 글꼴이 문서에 포함되어 있는지(true) 아니면 시스템 글꼴인지(false)를 나타냅니다.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


이 글꼴의 형식. 메타정보만 있고 바이너리 내용이 없을 경우 FontFormat.UNKNOWN를 반환할 수 있습니다.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


이 글꼴의 내용을 바이트 배열로 제공하거나, 사용할 수 없을 경우 null입니다.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


이 글꼴의 문자 집합.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


다음 템플릿으로 이 글꼴에 대한 디버그 정보를 반환합니다: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


이 글꼴 정보를 @font-face CSS 규칙으로 직렬화하고 지정된 writer에 씁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 출력 | java.io.Writer | 직렬화된 CSS를 받을 writer. |

