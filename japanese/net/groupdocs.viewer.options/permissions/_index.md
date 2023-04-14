---
title: Permissions
second_title: GroupDocs.Viewer for .NET API リファレンス
description: PDF ドキュメントの権限を定義します
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

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| AllowAll | `0` | 印刷、変更、およびデータ抽出を許可します。 |
| DenyPrinting | `1` | 印刷拒否 |
| DenyModification | `2` | コンテンツの変更、フォームへの入力、注釈の追加または変更を拒否します。 |
| DenyDataExtraction | `4` | テキストとグラフィックスの抽出を拒否します。 |
| DenyAll | `7` | 印刷、変更、およびデータ抽出を拒否します。 |

### 関連項目

* 名前空間 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->