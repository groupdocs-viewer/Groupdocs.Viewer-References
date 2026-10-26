---
title: "SpreadsheetFontInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Viewer 인스턴스에 로드된 스프레드시트 문서에서 하나의 폰트에 대한 메타정보와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer 인스턴스에 로드된 스프레드시트 문서에서 하나의 폰트에 대한 메타정보와 바이너리 데이터를 캡슐화합니다. 스프레드시트 문서는 임베디드 폰트를 가질 수 없으므로, Viewer.getAllFonts() 메서드가 반환하는 경우 해당 폰트는 GroupDocs.Viewer가 실행되는 운영 체제에 설치됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 스타일이 없는 글꼴의 패밀리 이름으로, null이거나 비어 있지 않습니다. |
| [getStyle()](#getStyle--) | 이 폰트의 스타일 \\u2014 Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다. |
| [isStrikeout()](#isStrikeout--) | 폰트에 단일 취소선이 있는지 여부를 나타냅니다. |
| [isUnderline()](#isUnderline--) | 폰트에 밑줄이 있는지 여부를 나타냅니다. |
| [getColor()](#getColor--) | 이 폰트의 색상입니다. |
| [getCharset()](#getCharset--) | 이 글꼴의 문자 집합. |
| [getContent()](#getContent--) | 바이트 배열 형태의 이 폰트 콘텐츠입니다. |
| [getFormat()](#getFormat--) | 이 글꼴의 형식. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 이 폰트 정보를 @font-face at-rule으로 직렬화하고 지정된 writer에 씁니다. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


스타일이 없는 글꼴의 패밀리 이름으로, null이거나 비어 있지 않습니다.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


이 폰트의 스타일 \\u2014 Regular, Bold, Italic, 또는 BoldItalic일 수 있습니다.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


폰트에 단일 취소선이 있는지 여부를 나타냅니다.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


폰트에 밑줄이 있는지 여부를 나타냅니다.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


이 폰트의 색상입니다.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


이 글꼴의 문자 집합.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


바이트 배열 형태의 이 폰트 콘텐츠입니다. 메타 정보만 있는 경우 null일 수 있습니다.

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


이 글꼴의 형식.

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


이 폰트 정보를 @font-face at-rule으로 직렬화하고 지정된 writer에 씁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 출력 | java.io.Writer | 직렬화된 텍스트 데이터를 쓸 장치입니다. |

