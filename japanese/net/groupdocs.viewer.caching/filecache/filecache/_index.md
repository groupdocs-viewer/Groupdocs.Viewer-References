---
title: "FileCache"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "FileCachegroupdocs.viewer.caching/filecache クラスの新しいインスタンスを作成します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

[`FileCache`](../../filecache) クラスの新しいインスタンスを作成します。

```csharp
public FileCache(string cachePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| cachePath | String | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *cachePath* が null のときにスローされます。 |

### 関連項目

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

[`FileCache`](../../filecache) クラスの新しいインスタンスを作成します。

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| cachePath | String | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |
| cacheSubFolder | String | *cachePath* に追加するサブフォルダーです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *cachePath* が null のときにスローされます。 |
| ArgumentNullException | *cacheSubFolder* が null のときにスローされます。 |

### 関連項目

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
