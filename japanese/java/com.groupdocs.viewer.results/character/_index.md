---
title: "文字"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "単一文字を含む相対位置の矩形を表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.viewer.results/character/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Character extends TextElement<Character>, Serializable
```

単一文字を含む相対位置の矩形を表します。


Character インターフェイスは、矩形で表される文字にアクセスし操作するための契約を定義します。
GroupDocs.Viewer コンポーネント内です。文字そのものなどの情報を取得するメソッドを提供します。
位置、および矩形のサイズ。


使用例:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List characters = viewInfo.getPages().get(0).getLines().get(0).getWords().get(0).getCharacters();
     Character character = characters.get(0);

     // Use the character object for further operations
 }
 
````


***Note:** The default implementation of this interface is CharacterImpl.*

