---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "封装在加载到 Viewer 实例的 Presentation 文档中使用的字体的元数据和二进制数据。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

封装在加载到 Viewer 实例的 Presentation 文档中使用的字体的元数据和二进制数据。此字体用于文档内容，可能嵌入在文档本身中，或安装在运行 GroupDocs.Viewer 的操作系统中。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 获取字体的族名称（永不为 null 或空）。 |
|
|  | [getStyle()](#getStyle--) | 获取字体的样式：Regular、Bold、Italic 或 BoldItalic。 |
|
|  | [isEmbedded()](#isEmbedded--) | 指示此字体是否嵌入在加载到 Viewer 实例的文档中。 |
|
|  | [getFormat()](#getFormat--) | 获取字体的格式（TrueType、OpenType 等）。 |
|
|  | [getContent()](#getContent--) | 获取字体的二进制内容，如果字体数据不可用则为 null。 |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 使用指定的 writer 将此字体信息序列化为 CSS @font-face 规则。 |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


获取字体的族名称（永不为 null 或空）。


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


获取字体的样式：Regular、Bold、Italic 或 BoldItalic。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


指示此字体是否嵌入在加载到 Viewer 实例的文档中。注意：Spreadsheet 文档无法包含嵌入字体，因此对它们始终返回 false。


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


获取字体的格式（TrueType、OpenType 等）。如果仅有元数据可用，则返回 FontFormat.Unknown。


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


获取字体的二进制内容，如果字体数据不可用则为 null。


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


使用指定的 writer 将此字体信息序列化为 CSS @font-face 规则。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | output | java.io.Writer | 用于写入 CSS 的 writer（不能为空） |
|

