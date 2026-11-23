---
title: "FontsToExclude"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "HTMLドキュメントから除外するフォント名のリストです。"
type: docs
weight: 40
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---

## HtmlViewOptions.FontsToExclude property

HTMLドキュメントから除外するフォント名のリストです。

```csharp
public List<string> FontsToExclude { get; set; }
```

### 備考

HTML ドキュメントに追加されるフォントは出力ビューの安定性を向上させますが、同時にレンダリング結果のサイズも増加させます。このオプションにより、安定性と出力サイズのバランスを取ることができます。一般的で多くのシステムにインストールされているフォント名を含めてください。

このプロパティは、[`ExcludeFonts`](../excludefonts) オプションが無効になっている場合にのみ有効であることに注意してください。

詳細とコード例については、[documentation](https://docs.groupdocs.com/viewer/net/exclude-fonts/) を参照してください。

### 関連項目

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
