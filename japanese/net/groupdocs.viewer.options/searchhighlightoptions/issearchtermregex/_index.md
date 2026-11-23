---
title: "IsSearchTermRegEx"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "検索語を正規表現として扱うかテキストリテラルとして扱うかを示す値を取得または設定します。デフォルトは false で、テキストリテラルとして扱います。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

検索語が正規表現として扱われるかテキストリテラルとして扱われるかを示す値を取得または設定します。デフォルトは `false` で、テキストリテラルとして扱います。

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### 備考

`true` の場合、[`SearchTerm`](../searchterm) は .NET の Regex パターンとして解釈されます。

`false` の場合、[`SearchTerm`](../searchterm) はドキュメント内でテキストリテラルとして検索されます。

### 関連項目

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
