---
title: "Search"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ロードされたドキュメント内でテキスト検索を実行し、ロードされたオプションに従って見つかった場合はハイライトします。"
type: docs
weight: 80
url: /ja/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

読み込まれたドキュメントで、ロードされたオプションに従ってテキスト検索と（見つかった場合の）ハイライトを実行します。

```csharp
public void Search(SearchHighlightOptions options)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| options | SearchHighlightOptions | 検索およびハイライトのオプションで、検索するテキストフレーズを含みます。`null` にすることはできません。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *options* 引数が `null` のときにスローされます。 |

### 関連項目

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
