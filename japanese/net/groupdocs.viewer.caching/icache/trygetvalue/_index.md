---
title: "TryGetValue"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "このキーに関連付けられたエントリが存在する場合取得します。"
type: docs
weight: 30
url: /ja/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

このキーに関連付けられたエントリが存在する場合取得します。

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| パラメータ | 説明 |
| --- | --- |
| TEntry | エントリの型です。 |
| キー | 要求されたエントリを識別するキーです。 |
| 値 | 見つかった値または null です。 |

### 戻り値

```csharp
True
```

キーが見つかった場合です。

### 関連項目

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
