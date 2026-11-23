---
title: "FontStyles"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "문서에서 사용되는 글꼴의 4가지 가능한 스타일인 Regular, Bold, Italic 또는 Bold Italic을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

문서에서 사용되는 글꼴의 4가지 가능한 스타일을 나타냅니다: Regular, Bold, Italic, 또는 Bold Italic.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | bold/italic 플래그로부터 FontStyles 인스턴스를 생성합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [toString(int style)](#toString-int-) | 스타일 값을 사람이 읽을 수 있는 문자열로 변환합니다. |
|
|  | [getName()](#getName--) | 이 글꼴 스타일의 읽을 수 있는 이름을 반환합니다. |
|
|  | [isBold()](#isBold--) | 볼드 비트가 설정되어 있으면 true를 반환합니다. |
|
|  | [isItalic()](#isItalic--) | 이탤릭 비트가 설정되어 있으면 true를 반환합니다. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | 합집합 (C# 연산자 +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | 차집합 (C# 연산자 -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | 글꼴 스타일 이름을 FontStyles로 구문 분석합니다. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


bold/italic 플래그로부터 FontStyles 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


스타일 값을 사람이 읽을 수 있는 문자열로 변환합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | style | int | 글꼴 스타일 값 |
|

**Returns:**
java.lang.String - 글꼴 스타일의 문자열 표현

### getName() {#getName--}
```
public String getName()
```


이 글꼴 스타일의 읽을 수 있는 이름을 반환합니다.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


볼드 비트가 설정되어 있으면 true를 반환합니다.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


이탤릭 비트가 설정되어 있으면 true를 반환합니다.


**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


합집합 (C# 연산자 +)


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 첫 번째 | com.groupdocs.viewer.fonts.FontStyles |  |
| 두 번째 | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


차집합 (C# 연산자 -)


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 피감수 | com.groupdocs.viewer.fonts.FontStyles |  |
| 감수 | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


글꼴 스타일 이름을 FontStyles로 구문 분석합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| style | java.lang.String |  |
| 구문 분석된 | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - 성공 시 true, 그렇지 않으면 false

