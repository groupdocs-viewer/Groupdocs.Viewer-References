---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer 인스턴스에 로드된 WordProcessing 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Viewer 인스턴스에 로드된 WordProcessing 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서 내용에 사용되며 문서 자체에 포함되거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치됩니다.

불변 클래스. 해당 인스턴스는 GroupDocs.Viewer에 의해 생성되어 반환됩니다.
공개 API이며 일반적으로 사용자가 생성해서는 안 됩니다.
자세한 내용은 문서를 참조하십시오:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 폰트의 패밀리 이름(스타일 제외), 절대 null이거나 비어 있지 않습니다. |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | 폰트의 대체 패밀리 이름. |
|
|  | [getStyle()](#getStyle--) | 폰트 스타일 — Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다. |
|
|  | [isEmbedded()](#isEmbedded--) | 이 폰트가 문서에 포함되어 있는지 여부를 나타냅니다 (true이면 포함, false이면 시스템 폰트). |
|
|  | [getFormat()](#getFormat--) | 이 폰트의 형식. |
|
|  | [getContent()](#getContent--) | 이 폰트의 내용을 바이트 배열로 제공하거나, 사용할 수 없을 경우 null을 반환합니다. |
|
|  | [getCharset()](#getCharset--) | 이 폰트의 문자 집합. |
|
|  | [toString()](#toString--) | 다음 템플릿으로 이 폰트에 대한 디버그 정보를 반환합니다: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 이 폰트 정보를 @font-face CSS 규칙으로 직렬화하고 지정된 writer에 씁니다. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


폰트의 패밀리 이름(스타일 제외), 절대 null이거나 비어 있지 않습니다.


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


폰트의 대체 패밀리 이름. 없을 경우 빈 문자열을 반환합니다.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


폰트 스타일 — Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


이 폰트가 문서에 포함되어 있는지 여부를 나타냅니다 (true이면 포함, false이면 시스템 폰트).


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


이 폰트의 형식. 메타 정보만 있고 바이너리 내용이 없을 경우 FontFormat.UNKNOWN를 반환할 수 있습니다.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


이 폰트의 내용을 바이트 배열로 제공하거나, 사용할 수 없을 경우 null을 반환합니다.


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


이 폰트의 문자 집합.


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


다음 템플릿으로 이 폰트에 대한 디버그 정보를 반환합니다: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


이 폰트 정보를 @font-face CSS 규칙으로 직렬화하고 지정된 writer에 씁니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | output | java.io.Writer | 직렬화된 CSS를 받을 writer. |
|

