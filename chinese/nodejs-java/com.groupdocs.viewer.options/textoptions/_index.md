---
title: "TextOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "文本文件拆分为页面的选项。"
type: docs
weight: 32
url: /zh/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

文本文件拆分为页面的选项。

TextOptions 类提供在 GroupDocs.Viewer 组件中将文本文件拆分为页面的选项。它允许您控制文本文件如何划分为单独的页面，以便进行渲染和查看。

示例用法：

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextOptions()](#TextOptions--) | 初始化 TextOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | 获取页面上每行的最大字符数。 |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | 设置页面上每行的最大字符数。 |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | 获取每页的最大行数。 |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | 设置每页的最大行数。 |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


初始化 TextOptions 类的新实例。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


获取页面上每行的最大字符数。

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - 每页每行的最大字符数。
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


设置页面上每行的最大字符数。

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxCharsPerRow | int | 每页每行的最大字符数。 |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


获取每页的最大行数。

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - 最大行数。
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


设置每页的最大行数。

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxRowsPerPage | int | 最大行数。 |

