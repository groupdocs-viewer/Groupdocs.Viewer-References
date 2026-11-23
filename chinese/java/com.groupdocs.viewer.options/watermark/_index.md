---
title: "Watermark"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示文本水印。"
type: docs
weight: 37
url: /zh/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

表示文本水印。详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/add-text-watermark/)。


The Watermark 类表示 GroupDocs.Viewer 组件中的文本水印。
它用于定义并将水印应用于文档的渲染输出。


示例用法：

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | 初始化一个新的实例 |
Watermark
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 返回水印文本。 |
|
|  | [getColor()](#getColor--) | 返回水印颜色。 |
|
|  | [getColorAsHex()](#getColorAsHex--) | 以十六进制格式返回水印颜色。 |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 设置水印颜色。 |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | 设置水印颜色。 |
|
|  | [getPosition()](#getPosition--) | 返回水印位置。 |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | 设置水印位置。 |
|
|  | [getSize()](#getSize--) | 返回水印尺寸。 |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | 设置水印大小。 |
|
|  | [getFontName()](#getFontName--) | 返回用于水印的字体名称。 |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | 设置用于水印的字体名称。 |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


初始化一个新的实例
Watermark
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 水印文本。 |
|

### getText() {#getText--}
```
public final String getText()
```


返回水印文本。
此方法检索应用于文档的水印文本。


**Returns:**
java.lang.String - 水印文本。

### getColor() {#getColor--}
```
public final Color getColor()
```


返回水印颜色。
此方法检索应用于文档的水印颜色。


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - 水印颜色。

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


以十六进制格式返回水印颜色。
此方法检索应用于文档的水印颜色。


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - 十六进制格式的水印颜色。

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


设置水印颜色。
此方法设置应用于文档的水印颜色。


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.awt.Color | 要设置的水印颜色。 |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


设置水印颜色。
此方法设置应用于文档的水印颜色。


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | colorName | java.lang.String | 要设置的水印颜色。 |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


返回水印位置。
此方法返回应用于文档的水印位置。


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


设置水印位置。
此方法设置应用于文档的水印位置。


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | 水印位置。 |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


返回水印尺寸。
此方法检索应用于文档的水印大小。


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


设置水印大小。
此方法设置将应用于文档的水印大小。


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | 水印大小。 |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


返回用于水印的字体名称。


**Returns:**
java.lang.String - 用于水印的字体名称。

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


设置用于水印的字体名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 用于水印的字体名称。 |
|

