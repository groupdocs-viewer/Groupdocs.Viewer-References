---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。このフォントは元々ロードされた Viewer../groupdocs.viewer/viewer インスタンスのドキュメントで使用されていませんが、対象マシンで見つからないフォントの代替として機能します。代替フォントは WordProcessing フォーマット ファミリーにのみ存在します。"
type: docs
weight: 890
url: /ja/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。このフォントは元々ロードされた [`Viewer`](../../groupdocs.viewer/viewer) インスタンスのドキュメントで使用されていませんが、対象マシンで見つからないフォントの代替として機能します。代替フォントは WordProcessing フォーマット ファミリーにのみ存在します。

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | この代替フォントの内容はバイト配列として表されます。`null` になることはありません。 |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | スタイルなしの **substituted** フォントのファミリ名で、`null` または空文字列になることはありません。 |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | この代替（元ではない）フォントの形式です。TrueType、TrueType Collection、OpenType、Embedded OpenType のいずれかです。代替フォントはバイナリ内容が定義上利用可能なため、このプロパティが Unknown 値を返すことはありません。 |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | 対象マシンで見つからない元のフォントのファミリ名（スタイルなし）で、`null` または空文字列になることはありません。 |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | 元のフォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです。代替フォントは通常（必ずしもではありませんが）同じスタイルです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | このフォントデータに関するデバッグ情報を次のテンプレートで返します："original-name -&gt; substituted-name style, format" |

### 備考

不変（イミュータブル）構造体です。そのインスタンスは GroupDocs.Viewer のパブリック API によって生成・返却され、通常ユーザーが作成すべきではありません。詳細は [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) を参照してください。

### 関連項目

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
