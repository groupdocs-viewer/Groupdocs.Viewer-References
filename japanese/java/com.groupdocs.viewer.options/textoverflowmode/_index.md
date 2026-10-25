---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "スプレッドシート文書を HTML にレンダリングする際のテキストオーバーフローモードを定義します。"
type: docs
weight: 46
url: /ja/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

スプレッドシート文書を HTML にレンダリングする際のテキストオーバーフローモードを定義します。


TextOverflowMode 列挙体は、GroupDocs.Viewer コンポーネントでテキストのオーバーフローを処理するさまざまなモードを表します。
利用可能な領域を超えるテキストの表示方法を制御できる、事前定義されたオプションのセットを提供します。
スプレッドシート ドキュメントを HTML にレンダリングする際のセル内のスペース。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


使用例:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | 空でなくても次のセルにオーバーレイします。 |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | 空の場合にのみ次のセルにオーバーレイします。 |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | テキストに合わせて列を展開します。 |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | オーバーフローしたテキストを非表示にします。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


空でなくても次のセルにオーバーレイします。
このモードでは、隣接するセルの内容に関係なく、テキストがオーバーフローして隣のセルに入ることを許可します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


空の場合にのみ次のセルにオーバーレイします。
このモードでは、隣接するセルが空の場合にのみ、テキストがオーバーフローして隣のセルに入ることを許可します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


テキストに合わせて列を展開します。
このモードは、オーバーフローしたテキストを収容できるように列の幅を自動的に調整します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


オーバーフローしたテキストを非表示にします。
このモードはオーバーフローしたテキストを非表示にし、表示されないようにします。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


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
