---
title: "Line"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Linegroupdocs.viewer.results/line クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

[`Line`](../../line) クラスの新しいインスタンスを初期化します。

```csharp
public Line()
```

### 関連項目

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

[`Line`](../../line) クラスの新しいインスタンスを初期化します。

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 行 | String | 行です。 |
| x | Double | 行を含む矩形が始まるページレイアウト上の最上部左側の点の X 座標です。 |
| y | Double | 行を含む矩形が始まるページレイアウト上の最上部左側の点の Y 座標です。 |
| width | Double | 行を含む矩形の幅（ピクセル単位）です。 |
| height | Double | ラインを含む矩形の高さ（ピクセル）。 |
| 単語 | List`1 | 行に含まれる単語。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException |  *line* が null または空の場合にスローされます。 |
| ArgumentNullException |  *words* が null の場合にスローされます。 |

### 関連項目

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
