---
title: "FontStyles"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントで使用されるフォントの 4 つの可能なスタイル（Regular、Bold、Italic、Bold Italic）を表します"
type: docs
weight: 810
url: /ja/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

文書で使用されるフォントの 4 つの可能なスタイルを表します: Regular、Bold、Italic、または Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | 指定された bold と italic フラグから 1 つの [`FontStyles`](../fontstyles) インスタンスを作成します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | この [`FontStyles`](../fontstyles) インスタンスに **bold** フラグが有効 (`true`) か無効 (`false`) かを示します |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | この [`FontStyles`](../fontstyles) インスタンスに **italic** フラグが有効 (`true`) か無効 (`false`) かを示します |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | このフォントスタイルの名前 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | この [`FontStyles`](../fontstyles) インスタンスが指定されたものと等しいかどうかを示します |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | この [`FontStyles`](../fontstyles) インスタンスが指定された未キャストの値と等しいかどうかを示します |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | このインスタンスのハッシュコードを返します |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | このフォントスタイルの名前を返します（[`Name`](./name) と同じ） |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | 指定された生文字列をフォントスタイル名として解析しようとします |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | 指定された 2 つのフォントスタイルを結合（マージ）し、フラグが統合（和集合）された新しい結果のフォントスタイルを生成します |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | 2 つの [`FontStyles`](../fontstyles) 値が等しいかどうかを確認します |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | 指定された [`FontStyles`](../fontstyles) インスタンスを 10 進数範囲 [0..3] の等価オクテット（8 ビットビットフィールド）にキャストします |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | 2 つの [`FontStyles`](../fontstyles) 値が等しくないかどうかを確認します |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | 第1の（被減数）指定フォントスタイルから第2の（減数）指定フォントスタイルを減算し、第二オペランドに存在しない第1オペランドのフラグのみが残る新しい結果のフォントスタイルを生成します |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Bold フォントスタイル（bold のみ、italic なし） |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | BoldItalic フォントスタイル（bold と italic が同時） |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Italic フォントスタイル（italic のみ、bold なし） |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Regular フォントスタイル、デフォルト値（bold と italic がない） |

### 備考

便利な API と結合操作を備えたイミュータブル構造体

### 関連項目

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
