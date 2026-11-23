---
title: "Character"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示一个相对定位的矩形，包含单个字符。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

表示一个相对定位的矩形，包含单个字符。


Character 接口定义了访问和操作由矩形表示的字符的契约
在 GroupDocs.Viewer 组件中。它提供了检索字符本身等信息的方法，
位置以及矩形的大小。


示例用法：

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

