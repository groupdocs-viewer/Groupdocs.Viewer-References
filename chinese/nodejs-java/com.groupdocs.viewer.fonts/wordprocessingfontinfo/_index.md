---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "封装来自加载到 Viewer 实例的 WordProcessing 文档中的单个字体的元信息和二进制数据。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

封装来自 WordProcessing 文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。此字体用于文档内容，可能嵌入在文档本身中，或已安装在运行 GroupDocs.Viewer 的操作系统中。

不可变类。其实例由 GroupDocs.Viewer 公共 API 生成并返回，通常不应由用户创建。有关详细信息，请参阅文档：https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 字体的族名称，不含样式，永不为 null 或空。 |
| [getAltFamilyName()](#getAltFamilyName--) | 字体的替代族名称。 |
| [getStyle()](#getStyle--) | 字体的样式 — 可能是 Regular、Bold、Italic 或 BoldItalic。 |
| [isEmbedded()](#isEmbedded--) | 指示此字体是嵌入在文档中 (true) 还是系统字体 (false)。 |
| [getFormat()](#getFormat--) | 此字体的格式。 |
| [getContent()](#getContent--) | 此字体的内容，以字节数组形式表示，如果不可用则为 null。 |
| [getCharset()](#getCharset--) | 此字体的字符集。 |
| [toString()](#toString--) | 返回关于此字体的调试信息，使用以下模板："name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 将此字体信息序列化为 @font-face CSS 规则并写入指定的 writer。 |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


字体的族名称，不含样式，永不为 null 或空。

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


字体的替代族名称。如果缺失，则返回空字符串。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


字体的样式 — 可能是 Regular、Bold、Italic 或 BoldItalic。

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


指示此字体是嵌入在文档中 (true) 还是系统字体 (false)。

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


此字体的格式。如果只有元信息而缺少二进制内容，可能返回 FontFormat.UNKNOWN。

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


此字体的内容，以字节数组形式表示，如果不可用则为 null。

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


此字体的字符集。

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


返回关于此字体的调试信息，使用以下模板："name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


将此字体信息序列化为 @font-face CSS 规则并写入指定的 writer。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输出 | java.io.Writer | 接收序列化 CSS 的 writer。 |

