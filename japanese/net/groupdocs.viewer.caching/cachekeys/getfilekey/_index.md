---
title: "GetFileKey"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

ファイルを表すキャッシュエントリの一意の識別子を返します。

```csharp
public static string GetFileKey(string extension)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 拡張子 | String | ファイル名のサフィックス（ピリオド "." を含む）例: ".doc"。 |

### 戻り値

ファイルを表すキャッシュエントリの一意の識別子です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *extension* が null または空の場合にスローされます。 |

### 関連項目

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
