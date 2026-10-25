---
title: "SearchHighlightOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Viewer../groupdocs.viewer/viewer クラスにロードされたドキュメント内のテキストを検索およびハイライトするためのオプションを提供します"
type: docs
weight: 500
url: /ja/net/groupdocs.viewer.options/searchhighlightoptions/
---

## SearchHighlightOptions class

ドキュメント内のテキストを検索およびハイライトするためのオプションを提供します。ロード先は [`Viewer`](../../groupdocs.viewer/viewer) クラスです

```csharp
public sealed class SearchHighlightOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SearchHighlightOptions](searchhighlightoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/searchhighlightoptions/backgroundcolor) { get; set; } | ハイライトの背景色を取得または設定します |
| [ForegroundColor](../../groupdocs.viewer.options/searchhighlightoptions/foregroundcolor) { get; set; } | ハイライトの前景（テキスト）色を取得または設定します |
| [IsSearchTermRegEx](../../groupdocs.viewer.options/searchhighlightoptions/issearchtermregex) { get; set; } | 検索語が正規表現として扱われるかテキストリテラルとして扱われるかを示す値を取得または設定します。デフォルトは `false` で、テキストリテラルとして扱います。 |
| [SearchTerm](../../groupdocs.viewer.options/searchhighlightoptions/searchterm) { get; set; } | 検索対象のテキスト（または、[`IsSearchTermRegEx`](./issearchtermregex) プロパティが `true` の場合は正規表現パターン）を取得または設定します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
