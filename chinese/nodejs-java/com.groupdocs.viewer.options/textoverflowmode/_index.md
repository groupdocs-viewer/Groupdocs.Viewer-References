---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "定义将电子表格文档渲染为 HTML 时的文本溢出模式。"
type: docs
weight: 46
url: /zh/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

定义将电子表格文档渲染为 HTML 时的文本溢出模式。

TextOverflowMode 枚举表示 GroupDocs.Viewer 组件中处理文本溢出的不同模式。它提供了一组预定义选项，可用于控制在将电子表格文档渲染为 HTML 时，文本超出单元格可用空间时的显示方式。有关详细信息，请参阅 [documentation][].

示例用法：

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## 字段

| 字段 | 描述 |
| --- | --- |
| [OVERLAY](#OVERLAY) | 即使相邻单元格不为空，也覆盖它们。 |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | 仅在相邻单元格为空时才覆盖它们。 |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | 展开列以适应文本。 |
| [HIDE_TEXT](#HIDE-TEXT) | 隐藏溢出文本。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


即使相邻单元格不为空，也覆盖它们。此模式允许文本溢出到相邻单元格，无论其内容如何。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


仅在相邻单元格为空时才覆盖它们。此模式仅在这些单元格为空时允许文本溢出到相邻单元格。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


展开列以适应文本。此模式会自动调整列宽，以容纳溢出的文本。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


隐藏溢出文本。此模式会隐藏溢出的文本，防止其显示。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
