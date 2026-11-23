---
title: "Size"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "包含水印尺寸。"
type: docs
weight: 30
url: /zh/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

包含水印尺寸。


Size 类表示 GroupDocs.Viewer 组件中水印的大小。
它提供了指定水印尺寸（如宽度和高度）的选项。


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
|  | [Size(byte relativeSize)](#Size-byte-) | 初始化一个新的实例 |
Size
类。
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | 表示适合页面的水印文本的最大尺寸。 |
|
|  | [HALF_SIZE](#HALF-SIZE) | 表示适合页面的水印文本的最大尺寸的一半。 |
|
|  | [ONE_THIRD](#ONE-THIRD) | 表示适合页面的水印文本的最大尺寸的三分之一。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | 返回相对于页面宽度的水印文本尺寸（百分比）。 |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


初始化一个新的实例
Size
类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | relativeSize | byte | 相对于页面尺寸的百分比大小。 |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


表示适合页面的水印文本的最大尺寸。


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


表示适合页面的水印文本的最大尺寸的一半。


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


表示适合页面的水印文本的最大尺寸的三分之一。


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


返回相对于页面宽度的水印文本尺寸（百分比）。


**Returns:**
byte - 水印文本的百分比大小。

