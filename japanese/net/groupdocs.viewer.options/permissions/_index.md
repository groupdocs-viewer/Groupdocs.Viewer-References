---
title: "権限"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PDF ドキュメントの権限を定義します。"
type: docs
weight: 430
url: /ja/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

PDF ドキュメントの権限を定義します。

```csharp
[Flags]
public enum Permissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AllowAll | `0` | 印刷、変更、データ抽出を許可します。 |
| DenyPrinting | `1` | 印刷を禁止します。 |
| DenyModification | `2` | コンテンツの変更、フォームへの入力、注釈の追加または変更を禁止します。 |
| DenyDataExtraction | `4` | テキストとグラフィックの抽出を禁止します。 |
| DenyAll | `7` | 印刷、コンテンツの変更、データ抽出を禁止します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
