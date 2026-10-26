---
title: "TextOverflowMode"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを定義します。"
type: docs
weight: 46
url: /ja/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを定義します。

TextOverflowMode 列挙体は、GroupDocs.Viewer コンポーネントにおけるテキストオーバーフローの処理モードを表します。スプレッドシート ドキュメントを HTML にレンダリングする際、セル内の利用可能なスペースを超えるテキストの表示方法を制御できる事前定義されたオプションのセットを提供します。詳細については、[documentation][] を参照してください。

使用例:

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
## フィールド

| フィールド | 説明 |
| --- | --- |
| [OVERLAY](#OVERLAY) | 空でないセルでも次のセルにオーバーレイします。 |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | セルが空の場合にのみ次のセルにオーバーレイします。 |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | テキストに合わせて列を拡張します。 |
| [HIDE_TEXT](#HIDE-TEXT) | オーバーフローしたテキストを非表示にします。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


空でないセルでも次のセルにオーバーレイします。このモードでは、セルの内容に関係なくテキストが隣接するセルにオーバーフローすることを許可します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


セルが空の場合にのみ次のセルにオーバーレイします。このモードでは、隣接するセルが空の場合に限りテキストがオーバーフローすることを許可します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


テキストに合わせて列を拡張します。このモードは、オーバーフローしたテキストを収容できるように列幅を自動的に調整します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


オーバーフローしたテキストを非表示にします。このモードは、テキストが表示されないように隠します。

詳細については、[documentation][] を参照してください。


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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
