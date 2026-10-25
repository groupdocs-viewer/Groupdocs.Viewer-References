---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントを JPG 形式でレンダリングするためのオプションを提供します。詳細はこのページ https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ とその子ページをご覧ください。"
type: docs
weight: 350
url: /ja/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

ドキュメントを JPG 形式にレンダリングするオプションを提供します。詳細については、この [page](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) とその子項目を参照してください。

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | `[`JpgViewOptions`](../jpgviewoptions)` クラスのインスタンスを初期化します。 |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | `[`JpgViewOptions`](../jpgviewoptions)` クラスのインスタンスを初期化します。 |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | `[`JpgViewOptions`](../jpgviewoptions)` クラスのインスタンスを初期化します。 |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | `[`JpgViewOptions`](../jpgviewoptions)` クラスのインスタンスを初期化します。 |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | `[`JpgViewOptions`](../jpgviewoptions)` クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブファイルのビューオプションです。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD図面のビューオプションです。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントのデフォルトフォントを設定します。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | メールメッセージのビューオプションです。 |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | テキスト抽出を有効にします。 |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | 出力画像の高さ（ピクセル単位）を設定します。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メールストレージデータファイルのビューオプションです。 |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | 出力画像の最大高さ（ピクセル単位）を設定します。 |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | 出力画像の最大幅（ピクセル単位）を設定します。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlookデータファイルのビューオプションです。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDFドキュメントのビューオプションです。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーションファイルのビューオプションです。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルのビューオプションです。 |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | 出力画像の品質を設定します。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` に設定するとコメントの描画が無効になります。デフォルトは `false` で、すべてのコメントが表示されます。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 非表示ページの描画を有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 一部の形式でノートと注釈の描画を有効にします |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシートファイルのビューオプションです。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキストファイルのビューオプションです。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visioファイルのビューオプションです。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 各ページに適用されるテキスト透かしです。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Webファイルのビューオプションです。 |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | 出力画像の幅（ピクセル単位）を設定します。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | ワードプロセッシングファイルのビューオプションです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | ページに時計回りの回転を適用します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | ページの回転です。 |

### 関連項目

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
