---
title: "Line"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示一个相对定位的矩形，包含单行。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

表示一个相对定位的矩形，包含单行。


Line 接口定义了访问和操作由矩形表示的线的契约
在 GroupDocs.Viewer 组件中。它提供用于检索信息的方法，例如行文本，
位置以及矩形的大小。


示例用法：

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWords()](#getWords--) | 检索行中包含的单词。 |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | 设置行中包含的单词。 |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


检索行中包含的单词。


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - 行中包含的单词。

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


设置行中包含的单词。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | 行中包含的单词。 |
|

