---
title: "GetResourceFilter"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "キャッシュエントリを検索するフィルタ文字列を返します。対象は Resourcegroupdocs.viewer.results/resource オブジェクトです。"
type: docs
weight: 60
url: /ja/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

キャッシュエントリを検索するフィルタ文字列を返します。対象は [`Resource`](../../../groupdocs.viewer.results/resource) オブジェクトです。

```csharp
public static string GetResourceFilter(int pageNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号です。 |

### 戻り値

キャッシュエントリを検索するフィルタ文字列。対象は [`Resource`](../../../groupdocs.viewer.results/resource) オブジェクトです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *pageNumber* が 0 以下のときにスローされます。 |

### 関連項目

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
