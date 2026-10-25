---
title: "MaxItemsInFolder"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.options/outlookoptions/maxitemsinfolder/
---

## OutlookOptions.MaxItemsInFolder property

1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。

```csharp
public int MaxItemsInFolder { get; set; }
```

### 備考

Outlook データ ファイルは大きくなることがあり、すべてのメッセージを取得するのにかなり時間がかかる場合があります。このプロパティはレンダリングされるメッセージまたはアイテムの最大数を制限します。デフォルト値は `50` です。すべてのメッセージをレンダリングするには、値を `0` に設定します。

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/render-outlook-data-files/#limit-the-number-of-folder-items-to-render) を参照してください。

### 関連項目

* class [OutlookOptions](../../outlookoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
