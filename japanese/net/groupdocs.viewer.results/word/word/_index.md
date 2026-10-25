---
title: "Word"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Wordgroupdocs.viewer.results/word クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

[`Word`](../../word) クラスの新しいインスタンスを初期化します。

```csharp
public Word()
```

### 関連項目

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

[`Word`](../../word) クラスの新しいインスタンスを初期化します。

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| 単語 | String | 単語です。 |
| x | Double | 単語を含む矩形が始まるページレイアウト上の最上部左側の点の X 座標です。 |
| y | Double | 単語を含む矩形が始まるページレイアウト上の最上部左側の点の Y 座標です。 |
| width | Double | 単語を含む矩形の幅です。 |
| height | Double | 単語を含む矩形の高さです。 |
| 文字 | List`1 | 単語に含まれる文字。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *word* が null または空の場合にスローされます。 |
| ArgumentNullException | *characters* が null の場合にスローされます。 |

### 関連項目

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
