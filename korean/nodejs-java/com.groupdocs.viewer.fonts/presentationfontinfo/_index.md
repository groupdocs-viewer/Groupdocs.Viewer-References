---
title: "PresentationFontInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Viewer 인스턴스에 로드된 Presentation 문서에서 사용되는 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Viewer 인스턴스에 로드된 Presentation 문서에서 사용되는 글꼴의 메타데이터와 바이너리 데이터를 캡슐화합니다. 이 글꼴은 문서 내용에 사용되며 문서 자체에 포함되어 있거나 GroupDocs.Viewer가 실행되는 운영 체제에 설치될 수 있습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 폰트 패밀리 이름을 가져옵니다 (절대 null이거나 비어 있지 않음). |
| [getStyle()](#getStyle--) | 폰트 스타일을 가져옵니다: Regular, Bold, Italic, 또는 BoldItalic. |
| [isEmbedded()](#isEmbedded--) | 이 폰트가 Viewer 인스턴스에 로드된 문서에 포함되어 있는지 여부를 나타냅니다. |
| [getFormat()](#getFormat--) | 폰트 형식을 가져옵니다 (TrueType, OpenType 등). |
| [getContent()](#getContent--) | 바이너리 폰트 콘텐츠를 가져오며, 폰트 데이터가 없을 경우 null을 반환합니다. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 지정된 writer를 사용하여 이 폰트 정보를 CSS @font-face 규칙으로 직렬화합니다. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


폰트 패밀리 이름을 가져옵니다 (절대 null이거나 비어 있지 않음).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


폰트 스타일을 가져옵니다: Regular, Bold, Italic, 또는 BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


이 폰트가 Viewer 인스턴스에 로드된 문서에 포함되어 있는지 여부를 나타냅니다. 참고: 스프레드시트 문서는 임베디드 폰트를 포함할 수 없으므로 항상 false를 반환합니다.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


폰트 형식을 가져옵니다 (TrueType, OpenType 등). 메타데이터만 있는 경우 FontFormat.Unknown을 반환합니다.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


바이너리 폰트 콘텐츠를 가져오며, 폰트 데이터가 없을 경우 null을 반환합니다.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


지정된 writer를 사용하여 이 폰트 정보를 CSS @font-face 규칙으로 직렬화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 출력 | java.io.Writer | CSS를 쓸 writer (null이면 안 됨) |

