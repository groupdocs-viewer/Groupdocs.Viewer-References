---
title: "FontSettings"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "TrueType フォントを検索するソースを操作するためのメソッドを提供します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

TrueType フォントを検索するソースを操作するためのメソッドを提供します。

FontSettings クラスは TrueType フォントの検索元を指定および管理するために使用されます。GroupDocs.Viewer API 用にフォントソースを追加およびリセットするメソッドを提供します。

使用例:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | ドキュメントをレンダリングする際に TrueType フォントを検索するソースを設定します。 |
| [resetFontSources()](#resetFontSources--) | 以前に設定されたフォントソースをリセットします。 |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


ドキュメントをレンダリングする際に TrueType フォントを検索するソースを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | 設定するフォントソース。 |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


以前に設定されたフォントソースをリセットします。

