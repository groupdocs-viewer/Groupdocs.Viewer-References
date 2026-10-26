---
title: "Position"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "定义水印位置。"
type: docs
weight: 43
url: /zh/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

定义水印位置。

Position 枚举表示 GroupDocs.Viewer 组件中水印的不同位置。它提供了一组预定义的位置，可用于在渲染过程中指定水印在文档或图像上的放置位置。

示例用法：

```

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
 
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | 对角线位置。 |
| [TOP_LEFT](#TOP-LEFT) | 左上位置。 |
| [TOP_CENTER](#TOP-CENTER) | 顶部居中位置。 |
| [TOP_RIGHT](#TOP-RIGHT) | 右上位置。 |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | 左下位置。 |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | 底部居中位置。 |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | 右下位置。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


对角线位置。此位置表示对角线对齐或放置。

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


左上位置。此位置表示左上角对齐或放置。

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


顶部居中位置。此位置表示顶部居中对齐或放置。

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


右上位置。此位置表示右上角对齐或放置。

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


左下位置。此位置表示左下角对齐或放置。

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


底部居中位置。此位置表示底部居中对齐或放置。

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


右下位置。此位置表示右下角对齐或放置。

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
