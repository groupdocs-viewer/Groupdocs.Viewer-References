---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer 인스턴스에 로드된 Spreadsheet 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer 인스턴스에 로드된 Spreadsheet 문서에서 하나의 글꼴에 대한 메타 정보와 바이너리 데이터를 캡슐화합니다. Spreadsheet 문서는 임베디드 글꼴을 가질 수 없으므로, Viewer.getAllFonts() 메서드가 반환하는 경우 이 특정 글꼴은 GroupDocs.Viewer가 실행되는 운영 체제에 설치됩니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 폰트의 패밀리 이름(스타일 제외), 절대 null이거나 비어 있지 않습니다. |
|
|  | [getStyle()](#getStyle--) | 이 글꼴의 스타일 \u2014 Regular, Bold, Italic 또는 BoldItalic일 수 있습니다. |
|
|  | [isStrikeout()](#isStrikeout--) | 글꼴이 단일 취소선인지 여부를 나타냅니다. |
|
|  | [isUnderline()](#isUnderline--) | 글꼴에 밑줄이 있는지 여부를 나타냅니다. |
|
|  | [getColor()](#getColor--) | 이 글꼴의 색상입니다. |
|
|  | [getCharset()](#getCharset--) | 이 폰트의 문자 집합. |
|
|  | [getContent()](#getContent--) | 이 글꼴의 내용을 바이트 배열로 제공합니다. |
|
|  | [getFormat()](#getFormat--) | 이 폰트의 형식. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 이 글꼴 정보를 @font-face at-rule 형태로 직렬화하고 지정된 writer에 씁니다. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


폰트의 패밀리 이름(스타일 제외), 절대 null이거나 비어 있지 않습니다.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


이 글꼴의 스타일 \u2014 Regular, Bold, Italic 또는 BoldItalic일 수 있습니다.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


글꼴이 단일 취소선인지 여부를 나타냅니다.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


글꼴에 밑줄이 있는지 여부를 나타냅니다.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


이 글꼴의 색상입니다.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


이 폰트의 문자 집합.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


이 글꼴의 내용을 바이트 배열로 제공합니다. 메타 정보만 있는 경우 null일 수 있습니다.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


이 폰트의 형식.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


이 글꼴 정보를 @font-face at-rule 형태로 직렬화하고 지정된 writer에 씁니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | output | java.io.Writer | 직렬화된 텍스트 데이터를 쓸 장치입니다. |
|

