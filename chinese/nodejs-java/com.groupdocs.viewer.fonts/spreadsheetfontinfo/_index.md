---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "封装来自加载到 Viewer 实例的电子表格文档中单个字体的元信息和二进制数据。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

封装来自电子表格文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。电子表格文档不能拥有嵌入字体，因此如果此特定字体由 Viewer.getAllFonts() 方法返回，则它已安装在运行 GroupDocs.Viewer 的操作系统中。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 字体的族名称，不含样式，永不为 null 或空。 |
| [getStyle()](#getStyle--) | 此字体的样式 — 可能是 Regular、Bold、Italic 或 BoldItalic。 |
| [isStrikeout()](#isStrikeout--) | 指示该字体是否为单一删除线。 |
| [isUnderline()](#isUnderline--) | 指示该字体是否有下划线。 |
| [getColor()](#getColor--) | 此字体的颜色。 |
| [getCharset()](#getCharset--) | 此字体的字符集。 |
| [getContent()](#getContent--) | 此字体的内容，以字节数组形式。 |
| [getFormat()](#getFormat--) | 此字体的格式。 |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 将此字体信息序列化为 @font-face 规则并写入指定的 writer。 |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


字体的族名称，不含样式，永不为 null 或空。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


此字体的样式 — 可能是 Regular、Bold、Italic 或 BoldItalic。

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


指示该字体是否为单一删除线。

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


指示该字体是否有下划线。

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


此字体的颜色。

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


此字体的字符集。

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


此字体的内容，以字节数组形式。如果仅有元信息，则可能为 null。

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


此字体的格式。

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


将此字体信息序列化为 @font-face 规则并写入指定的 writer。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输出 | java.io.Writer | 用于写入序列化文本数据的设备。 |

