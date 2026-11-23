---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを設定します。"
type: docs
weight: 550
url: /ja/net/groupdocs.viewer.options/textoverflowmode/
---

## TextOverflowMode enumeration

スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを設定します。

```csharp
public enum TextOverflowMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Overlay | `0` | 次のセルが空でなくても上書きします。 |
| OverlayIfNextIsEmpty | `1` | 次のセルが空の場合にのみ上書きします。デフォルト値。 |
| AutoFitColumn | `2` | テキストに合わせて列を拡張します。 |
| HideText | `3` | オーバーフローしたテキストを非表示にします。 |

### 備考

詳細については、[ドキュメント](https://docs.groupdocs.com/viewer/net/specify-rendering-options/#control-cell-text-overflow) を参照してください。

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
