---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PDF ドキュメントからロードされた Viewer../groupdocs.viewer/viewer インスタンス内のフォント 1 つのメタ情報とバイナリデータをカプセル化します。このフォントは文書内容で使用され、文書自体に埋め込まれるか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされます。"
type: docs
weight: 840
url: /ja/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

PDF ドキュメントから取得したフォント 1 つのメタ情報とバイナリデータを、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードしてカプセル化します。このフォントは文書内容で使用され、文書自体に埋め込まれるか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされます。

```csharp
public struct PdfFontInfo : IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | このフォントの内容をバイト配列として取得します。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは `null` を返します。 |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | このフォントの形式です。文書は次の形式のフォントを使用する場合があります：TrueType、TrueType Collection、OpenType、Embedded OpenType。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは Unknown 値を返します。 |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | このフォントが PDF ドキュメント内に埋め込まれ、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードされているか（`true`）、あるいはそうでないかを示します。 |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | GroupDocs.Viewer が実行されているオペレーティングシステムにこのフォントが存在（インストール）しているかどうかを示します。 |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | フォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |

### 関連項目

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
