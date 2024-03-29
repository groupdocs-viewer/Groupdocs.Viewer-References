---
title: GetAttachmentKey
second_title: GroupDocs.Viewer for .NET API リファレンス
description: 添付ファイルを表すキャッシュ エントリの一意の識別子を返します
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---
## CacheKeys.GetAttachmentKey method

添付ファイルを表すキャッシュ エントリの一意の識別子を返します。

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| attachmentId | String | 添付ファイルの一意の (単一ファイルのコンテキストでの) 識別子。 |

### 戻り値

添付ファイルを表すキャッシュ エントリの一意の識別子。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*attachmentId*null または空です。 |

### 関連項目

* class [CacheKeys](../../cachekeys)
* 名前空間 [GroupDocs.Viewer.Caching](../../cachekeys)
* 組み立て [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
