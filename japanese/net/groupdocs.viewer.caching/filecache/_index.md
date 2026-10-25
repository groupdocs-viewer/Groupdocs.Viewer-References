---
title: "FileCache"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ローカルのオンディスクキャッシュを表します。"
type: docs
weight: 990
url: /ja/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

ローカルのディスク上キャッシュを表します。

```csharp
public class FileCache : ICache
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FileCache](filecache#constructor)(string) | [`FileCache`](../filecache) クラスの新しいインスタンスを作成します。 |
| [FileCache](filecache#constructor_1)(string, string) | [`FileCache`](../filecache) クラスの新しいインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | キャッシュフォルダーへの相対パスまたは絶対パスです。 |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | [`CachePath`](./cachepath) に追加するサブフォルダーです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | ファイル名にフィルタが含まれるすべてのファイル名を返します。 |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | データをローカルディスクにシリアライズします。 |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | このキーに関連付けられたデータが存在する場合、デシリアライズします。 |

### 関連項目

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
