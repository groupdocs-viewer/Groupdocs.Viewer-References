---
title: "Word"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "単一単語を含む相対位置の矩形を表します。"
type: docs
weight: 26
url: /ja/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

単一単語を含む相対位置の矩形を表します。

Word インターフェイスは、GroupDocs.Viewer コンポーネント内の相対位置指定された矩形内の単語を表します。TextElement インターフェイスを拡張し、単語の内容にアクセスし操作するための追加メソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is WordImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCharacters()](#getCharacters--) | 単語に含まれる文字を取得します。 |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | 単語に含まれる文字を設定します。 |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


単語に含まれる文字を取得します。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - 文字のリスト。
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


単語に含まれる文字を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 文字 | java.util.List<com.groupdocs.viewer.results.Character> | 設定する文字のリストです。 |

