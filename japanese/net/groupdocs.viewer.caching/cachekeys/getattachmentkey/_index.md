---
title: "GetAttachmentKey"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "添付ファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

添付ファイルを表すキャッシュエントリの一意の識別子を返します。

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| attachmentId | String | 単一ファイルのコンテキストにおける添付ファイルの一意の識別子です。 |

### 戻り値

添付ファイルを表すキャッシュエントリの一意の識別子です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *attachmentId* が null または空の場合にスローされます。 |

### 関連項目

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
