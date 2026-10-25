---
title: "GetPageKey"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ページファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
weight: 50
url: /ja/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

ページファイルを表すキャッシュエントリの一意の識別子を返します。

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | ページ番号です。 |
| 拡張子 | String | ファイル名のサフィックス（ピリオド "." を含む）例: ".doc"。 |

### 戻り値

ページファイルを表すキャッシュエントリの一意の識別子です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *pageNumber* が 0 以下のときにスローされます。 |
| ArgumentException | *extension* が null または空の場合にスローされます。 |

### 関連項目

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
