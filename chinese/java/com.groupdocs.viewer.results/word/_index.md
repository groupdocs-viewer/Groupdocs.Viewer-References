---
title: "Word"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示一个相对定位的矩形，包含单个单词。"
type: docs
weight: 28
url: /zh/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

表示一个相对定位的矩形，包含单个单词。


Word 接口表示 GroupDocs.Viewer 组件中相对定位矩形内的一个单词。
它扩展了 TextElement 接口，并提供额外的方法来访问和操作单词内容。


示例用法：

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is WordImpl.*

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | 检索单词包含的字符。 |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | 设置单词包含的字符。 |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


检索单词包含的字符。


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - 字符列表。

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


设置单词包含的字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 字符 | java.util.List<com.groupdocs.viewer.results.Character> | 要设置的字符列表。 |
|

