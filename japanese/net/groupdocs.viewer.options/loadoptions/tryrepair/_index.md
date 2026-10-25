---
title: "TryRepair"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的な破損を修復しようとします。既定値は false です。"
type: docs
weight: 80
url: /ja/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

有効にすると、GroupDocs.Viewer は PDF ドキュメントの構造的破損を修復しようとします。デフォルト値は `false` です。

```csharp
public bool TryRepair { get; set; }
```

### 備考

この機能は PDF ドキュメントの次の問題に対処します：

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### 関連項目

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
