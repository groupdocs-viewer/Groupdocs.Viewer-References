---
title: "UnlinkTableOfContents"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "HTML または PDF にレンダリングする際に、このオプションを true に設定すると目次からのナビゲーションが無効になります。HTML レンダリングでは、相対リンクを持つ a タグが span タグに置き換えられ、機能は削除されますが視覚的な外観は保持されます。PDF レンダリングでは、目次がリンクなしのプレーンテキストとしてレンダリングされ、ドキュメントセクションへのリンクは付加されません。"
type: docs
weight: 110
url: /ja/net/groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents/
---

## WordProcessingOptions.UnlinkTableOfContents property

HTML または PDF にレンダリングする際、このオプションを `true` に設定すると目次からのナビゲーションを無効にできます。HTML レンダリングの場合、相対リンクを持つ `a` タグは `span` タグに置き換えられ、機能は削除されますが視覚的な外観は保持されます。PDF レンダリングの場合、目次はリンクなしのプレーンテキストとしてレンダリングされ、文書セクションへのリンクは含まれません。

```csharp
public bool UnlinkTableOfContents { get; set; }
```

### 備考

デフォルト値は `false` です。

詳細については、[ドキュメント](https://docs.groupdocs.com/viewer/net/render-word-documents/#unlink-table-of-contents) を参照してください。

### 関連項目

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
