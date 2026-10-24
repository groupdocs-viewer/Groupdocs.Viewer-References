---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "封装通过 GroupDocs.Viewer 在文字处理文档中使用的一个替代字体的元数据和二进制数据。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

封装通过 GroupDocs.Viewer 在 WordProcessing 文档中使用的一个替代字体的元数据和二进制数据。不可变类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | 构造函数，用于初始化所有字段。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 返回替代字体的族名（永不为 null）。 |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | 返回原始字体的族名（永不为 null）。 |
|
|  | [getStyle()](#getStyle--) | 返回原始字体的样式。 |
|
|  | [getContent()](#getContent--) | 返回替代字体的二进制内容（永不为 null）。 |
|
|  | [getFormat()](#getFormat--) | 返回替代字体的字体格式。 |
|
|  | [toString()](#toString--) | 返回描述此替代字体的字符串："original-name -> substituted-name style, format"。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 基于原始族、替代族和样式的相等性。 |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 使用实用方法将此字体序列化为 @font-face CSS 规则。 |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


构造函数，用于初始化所有字段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | 原始字体名称（系统中未找到） |
|
|  | substitutedFamilyName | java.lang.String | 替代字体名称（可用） |
|
|  | 样式 | com.groupdocs.viewer.fonts.FontStyles | 字体样式（Regular、Bold、Italic、BoldItalic） |
|
|  | content | byte[] | 替代字体的二进制内容（永不为 null） |
|
|  | 格式 | int | 字体格式（TrueType、OpenType 等） |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


返回替代字体的族名（永不为 null）。


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


返回原始字体的族名（永不为 null）。


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


返回原始字体的样式。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


返回替代字体的二进制内容（永不为 null）。


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


返回替代字体的字体格式。


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


返回描述此替代字体的字符串："original-name -> substituted-name style, format"。


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


基于原始族、替代族和样式的相等性。用于在 HashSet 或 HashMap（如 C# IEqualityComparer）中使用时的必需条件。


**Parameters:**
| 参数 | 类型 | 描述 |
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


使用实用方法将此字体序列化为 @font-face CSS 规则。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| output | java.io.Writer |  |

