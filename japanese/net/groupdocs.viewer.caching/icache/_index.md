---
title: "ICache"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "レンダリングされたドキュメントとドキュメントリソースのキャッシュを保存するために必要なメソッドを定義します。"
type: docs
weight: 1000
url: /ja/net/groupdocs.viewer.caching/icache/
---

## ICache interface

レンダリングされたドキュメントとドキュメントリソースのキャッシュを保存するために必要なメソッドを定義します。

```csharp
public interface ICache
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | フィルタに一致するすべてのキーを返します。 |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | キャッシュにキャッシュエントリを挿入します。 |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | このキーに関連付けられたエントリが存在する場合取得します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
