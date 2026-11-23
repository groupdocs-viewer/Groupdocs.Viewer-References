---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "Presentation ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、Viewer../groupdocs.viewer/viewer インスタンスにロードします。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。"
type: docs
weight: 850
url: /ja/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

Presentation ドキュメントから 1 つのフォントのメタ情報とバイナリ データをカプセル化し、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードします。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。

```csharp
public struct PresentationFontInfo : IFontInfo
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | このフォントの内容をバイト配列として取得します。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは `null` を返します。 |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | このフォントの形式です。文書は次の形式のフォントを使用する場合があります：TrueType、TrueType Collection、OpenType、Embedded OpenType。フォントのメタ情報のみでバイナリ内容が利用できない場合、このプロパティは Unknown 値を返します。 |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | このフォントがドキュメントに埋め込まれているか、[`Viewer`](../../groupdocs.viewer/viewer) インスタンスにロードされているか (`true`)、あるいはシステムフォントか (`false`) を示します。スプレッドシート ドキュメントは埋め込みフォントを保持できないため、このプロパティは常に `false` を返します。 |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | フォントのスタイル — Regular、Bold、Italic、または Bold Italic のいずれかです |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | このフォント情報を @font-face ルールとしてシリアライズし、指定されたテキストライターに書き込みます。 |

### 関連項目

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
