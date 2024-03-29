---
title: Line
second_title: GroupDocs.Viewer for .NET API リファレンス
description: の新しいインスタンスを初期化しますLinegroupdocs.viewer.results/lineclass.
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/line/line/
---
## Line() {#constructor}

の新しいインスタンスを初期化します[`Line`](../../line)class.

```csharp
public Line()
```

### 関連項目

* class [Line](../../line)
* 名前空間 [GroupDocs.Viewer.Results](../../line)
* 組み立て [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

の新しいインスタンスを初期化します[`Line`](../../line)class.

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| line | String | この線。 |
| x | Double | 行を含む四角形が始まるページ レイアウトの一番左の点の X 座標。 |
| y | Double | 行を含む四角形が始まるページ レイアウトの一番左の点の Y 座標。 |
| width | Double | 線を含む四角形の幅 (ピクセル単位)。 |
| height | Double | 線を含む四角形の高さ (ピクセル単位)。 |
| words | List`1 | 行に含まれる単語。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | スローされるタイミング*line*null または空です。 |
| ArgumentNullException | スローされるタイミング*words*無効である。 |

### 関連項目

* class [Word](../../word)
* class [Line](../../line)
* 名前空間 [GroupDocs.Viewer.Results](../../line)
* 組み立て [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
