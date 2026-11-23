---
title: "Line"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "単一行を含む相対位置の矩形を表します。"
type: docs
weight: 18
url: /ja/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

単一行を含む相対位置の矩形を表します。

Line インターフェイスは、GroupDocs.Viewer コンポーネント内で矩形で表される行へのアクセスおよび操作の契約を定義します。行のテキスト、位置、矩形のサイズなどの情報を取得するためのメソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWords()](#getWords--) | 行に含まれる単語を取得します。 |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | 行に含まれる単語を設定します。 |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


行に含まれる単語を取得します。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - 行に含まれる単語です。
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


行に含まれる単語を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | 行に含まれる単語。 |

