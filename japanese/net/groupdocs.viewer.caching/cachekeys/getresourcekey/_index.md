---
title: "GetResourceKey"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Resourcegroupdocs.viewer.results/resource オブジェクトを表すキャッシュエントリの一意の識別子を返します。"
type: docs
weight: 70
url: /ja/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

キャッシュエントリが表す [`Resource`](../../../groupdocs.viewer.results/resource) オブジェクトの一意の識別子を返します。

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号です。 |
| リソース | Resource | HTML リソースです。 |

### 戻り値

キャッシュエントリが表す [`Resource`](../../../groupdocs.viewer.results/resource) オブジェクトの一意の識別子です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *pageNumber* が 0 以下のときにスローされます。 |
| ArgumentNullException | *resource* が null の場合にスローされます。 |

### 関連項目

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
