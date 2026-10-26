---
title: "FontFormat"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "UsedFontInfo 클래스에 존재할 수 있는 모든 폰트 형식을 나타냅니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

UsedFontInfo 클래스에 존재할 수 있는 모든 글꼴 형식을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Unknown](#Unknown) | 알 수 없거나 잘못된 폰트 형식입니다. |
| [TrueType](#TrueType) | TrueType 폰트 형식 (TTF). |
| [OpenType](#OpenType) | OpenType 폰트 형식 (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection 폰트 형식 (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType 폰트 형식 (EOT). |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [toString(int format)](#toString-int-) | 형식 값을 사람이 읽을 수 있는 문자열로 변환합니다. |
### Unknown {#Unknown}
```
public static final int Unknown
```


알 수 없거나 잘못된 폰트 형식입니다.

### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType 폰트 형식 (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType 폰트 형식 (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection 폰트 형식 (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded OpenType 폰트 형식 (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


형식 값을 사람이 읽을 수 있는 문자열로 변환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 형식 | int | 폰트 형식 값 |

**Returns:**
java.lang.String - 폰트 형식의 문자열 표현
