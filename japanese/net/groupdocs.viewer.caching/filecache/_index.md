---
title: FileCache
second_title: GroupDocs.Viewer for .NET API リファレンス
description: ローカルのディスク上のキャッシュを表します
type: docs
weight: 20
url: /ja/net/groupdocs.viewer.caching/filecache/
---
## FileCache class

ローカルのディスク上のキャッシュを表します。

```csharp
public class FileCache : ICache
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [FileCache](filecache#constructor)(string) | の新しいインスタンスを作成します[`FileCache`](../filecache)class. |
| [FileCache](filecache#constructor_1)(string, string) | の新しいインスタンスを作成します[`FileCache`](../filecache)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | キャッシュ フォルダーへの相対パスまたは絶対パス。 |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | に追加するサブフォルダー[`CachePath`](./cachepath). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | filename にフィルターを含むすべてのファイル名を返します。 |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | データをローカル ディスクにシリアル化します。 |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | 存在する場合、このキーに関連付けられたデータを逆シリアル化します. |

### 関連項目

* interface [ICache](../icache)
* 名前空間 [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
