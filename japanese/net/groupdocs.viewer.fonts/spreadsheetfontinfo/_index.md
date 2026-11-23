---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Spreadsheet ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、Viewer../groupdocs.viewer/viewer インスタンスにロードします。スプレッドシート ドキュメントは埋め込みフォントを持てないため、`GetAllFonts../groupdocs.viewer/viewer/getallfonts` メソッドで返されたこの特定のフォントは、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。"
type: docs
weight: 870
url: /ja/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

Spreadsheet ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードします。スプレッドシート ドキュメントは埋め込みフォントを持てないため、[`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts) メソッドで返されたこの特定のフォントは、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | このフォントの文字セット |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | このフォントの色 |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | このフォントの内容をバイト配列として取得します。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは `null` を返します。 |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | このフォントの形式 |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | フォントが単一の取り消し線かどうかを示します |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | フォントに下線があるかどうかを示します |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | このフォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |

### 関連項目

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
