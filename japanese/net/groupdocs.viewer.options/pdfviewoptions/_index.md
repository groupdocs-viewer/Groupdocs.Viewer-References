---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントを PDF 形式でレンダリングするためのオプションを含みます。詳細は documentationhttps//docs.groupdocs.com/viewer/net/renderingtopdf/ を参照してください。"
type: docs
weight: 420
url: /ja/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

ドキュメントを PDF 形式にレンダリングするオプションが含まれています。詳細については、[documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。

```csharp
public class PdfViewOptions : ViewOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | [`PdfViewOptions`](../pdfviewoptions) クラスのインスタンスを初期化します。 |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | [`PdfViewOptions`](../pdfviewoptions) クラスのインスタンスを初期化します。 |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | [`PdfViewOptions`](../pdfviewoptions) クラスのインスタンスを初期化します。 |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | [`PdfViewOptions`](../pdfviewoptions) クラスのインスタンスを初期化します。 |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | [`PdfViewOptions`](../pdfviewoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブファイルのビューオプションです。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD図面のビューオプションです。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントのデフォルトフォントを設定します。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | メールメッセージのビューオプションです。 |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | 出力画像の高さ（ピクセル単位）を設定します。 |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | 出力画像の最大高さ（ピクセル単位）を設定します。 |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | 出力画像の最大幅（ピクセル単位）を設定します。 |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | 出力画像の幅（ピクセル単位）を設定します。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メールストレージデータファイルのビューオプションです。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlookデータファイルのビューオプションです。 |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | さまざまなオプションを使用した最適化手法を適用して、出力 PDF ファイルのサイズを削減します。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDFドキュメントのビューオプションです。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーションファイルのビューオプションです。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルのビューオプションです。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` に設定するとコメントの描画が無効になります。デフォルトは `false` で、すべてのコメントが表示されます。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 非表示ページの描画を有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 一部の形式でノートと注釈の描画を有効にします |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | 出力 PDF ドキュメントのセキュリティオプションを設定します。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシートファイルのビューオプションです。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキストファイルのビューオプションです。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visioファイルのビューオプションです。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 各ページに適用されるテキスト透かしです。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Webファイルのビューオプションです。 |
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
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
