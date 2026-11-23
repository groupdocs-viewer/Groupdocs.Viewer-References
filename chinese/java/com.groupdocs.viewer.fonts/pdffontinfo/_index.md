---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "封装从加载到 Viewer 实例的 PDF 文档中提取的单个字体的元信息和二进制数据。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

封装来自 PDF 文档的单个字体的元信息和二进制数据，已加载到 Viewer 实例中。


此字体在文档内容中使用，并且是以下之一：

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF 字体提取使用的内部构造函数。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 获取字体族名称。 |
|
|  | [getStyle()](#getStyle--) | 获取此字体的样式。 |
|
|  | [isEmbedded()](#isEmbedded--) | 返回字体是否嵌入在 PDF 文档中。 |
|
|  | [isInstalled()](#isInstalled--) | 返回字体是否已安装在操作系统中。 |
|
|  | [getFormat()](#getFormat--) | 返回字体的文件格式。 |
|
|  | [getContent()](#getContent--) | 返回字体的二进制内容。 |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 将此字体序列化为 CSS @font-face 规则。 |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF 字体提取使用的内部构造函数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | familyName | java.lang.String | 字体族名称 |
|
|  | 样式 | com.groupdocs.viewer.fonts.FontStyles | 样式 (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | 如果字体嵌入在 PDF 中，则为 true |
|
|  | isInstalled | boolean | 如果字体已安装在操作系统中，则为 true |
|
|  | content | byte[] | 二进制字体数据 (可为空) |
|
|  | 格式 | int | 字体文件格式 |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


获取字体族名称。


**Returns:**
java.lang.String - 族名称字符串 (永不为 null 或 空)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


获取此字体的样式。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - 字体样式

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


返回字体是否嵌入在 PDF 文档中。


**Returns:**
boolean - 如果已嵌入，则为 true

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


返回字体是否已安装在操作系统中。


**Returns:**
boolean - 如果已安装，则为 true

### getFormat() {#getFormat--}
```
public int getFormat()
```


返回字体的文件格式。


**Returns:**
int - 字体格式枚举

### getContent() {#getContent--}
```
public byte[] getContent()
```


返回字体的二进制内容。


**Returns:**
byte[] - 字节数组或如果不可用则为 null

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


将此字体序列化为 CSS @font-face 规则。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | output | java.io.Writer | 用于写入 CSS 的 writer |
|

