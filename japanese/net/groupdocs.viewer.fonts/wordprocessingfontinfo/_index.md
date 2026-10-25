---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。このフォントは Viewer../groupdocs.viewer/viewer インスタンスにロードされたドキュメントで使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。"
type: docs
weight: 880
url: /ja/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

WordProcessing ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードします。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | フォントの代替ファミリ名です。欠落している場合は空文字列になります。 |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | このフォントの文字セット |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | このフォントの内容をバイト配列として取得します。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは `null` を返します。 |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | このフォントの形式です。文書は次の形式のフォントを使用する場合があります：TrueType、TrueType Collection、OpenType、Embedded OpenType。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは Unknown 値を返します。 |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | このフォントがドキュメントに埋め込まれているか、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードされているか (`true`)、あるいはシステムフォントか (`false`) を示します。 |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | フォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | このフォントデータに関するデバッグ情報を次のテンプレートで返します: "name style, embedded/system, format" |

### 備考

不変（イミュータブル）構造体です。そのインスタンスは GroupDocs.Viewer のパブリック API によって生成・返却され、通常ユーザーが作成すべきではありません。詳細は [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/) を参照してください。

### 関連項目

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
