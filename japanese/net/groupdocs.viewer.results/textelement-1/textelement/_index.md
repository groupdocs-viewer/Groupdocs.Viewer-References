---
title: "TextElement"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "TextElementgroupdocs.viewer.results/textelement1 クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

[`TextElement`](../../textelement-1) クラスの新しいインスタンスを初期化します。

```csharp
public TextElement()
```

### 関連項目

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

[`TextElement`](../../textelement-1) クラスの新しいインスタンスを初期化します。

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 値 | T | テキスト要素の値。 |
| x | Double | ページレイアウト上で要素を含む矩形が始まる最上部左側点の X 座標。 |
| y | Double | ページレイアウト上で要素を含む矩形が始まる最上部左側点の Y 座標。 |
| width | Double | 要素を含む矩形の幅（ピクセル単位）。 |
| height | Double | 要素を含む矩形の高さ（ピクセル単位）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *value* が null のときにスローされます。 |
| ArgumentException | *width* が 0 以下の場合にスローされます。 |
| ArgumentException | *height* が 0 以下の場合にスローされます。 |

### 関連項目

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
