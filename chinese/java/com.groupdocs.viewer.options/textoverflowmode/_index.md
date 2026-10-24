---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "定义将电子表格文档渲染为 HTML 时的文本溢出模式。"
type: docs
weight: 46
url: /zh/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

定义将电子表格文档渲染为 HTML 时的文本溢出模式。


The TextOverflowMode 枚举表示在 GroupDocs.Viewer 组件中处理文本溢出的不同模式。
它提供了一组预定义选项，可用于控制文本在超出可用范围时的显示方式
在将电子表格文档渲染为 HTML 时，单元格中的空间。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


示例用法：

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | 即使相邻单元格不为空，也覆盖它们。 |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | 仅在相邻单元格为空时才覆盖它们。 |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | 展开列以适应文本。 |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | 隐藏溢出文本。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


即使相邻单元格不为空，也覆盖它们。
此模式允许文本溢出到相邻单元格中，而不考虑其内容。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


仅在相邻单元格为空时才覆盖它们。
此模式仅在相邻单元格为空时才允许文本溢出到这些单元格。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


展开列以适应文本。
此模式会自动调整列宽以容纳溢出的文本。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


隐藏溢出文本。
此模式隐藏溢出的文本，防止其显示。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


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
