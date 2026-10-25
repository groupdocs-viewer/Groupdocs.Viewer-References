---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ビューに関する情報を取得するオプションが含まれています。"
type: docs
weight: 580
url: /ja/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

ビューに関する情報を取得するオプションが含まれています。

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブファイルのビューオプションです。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD図面のビューオプションです。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントのデフォルトフォントを設定します。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | メールメッセージのビューオプションです。 |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | テキスト抽出を有効にします。 |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | 出力画像の高さ（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メールストレージデータファイルのビューオプションです。 |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | 出力画像の最大高さを設定します（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | 出力画像の最大幅を設定します（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlookデータファイルのビューオプションです。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDFドキュメントのビューオプションです。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーションファイルのビューオプションです。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルのビューオプションです。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` に設定するとコメントの描画が無効になります。デフォルトは `false` で、すべてのコメントが表示されます。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 非表示ページの描画を有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 一部の形式でノートと注釈の描画を有効にします |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシートファイルのビューオプションです。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキストファイルのビューオプションです。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visioファイルのビューオプションです。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Webファイルのビューオプションです。 |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | 出力画像の幅（ピクセル単位、PNG/JPG のレンダリング時のみ）。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | ワードプロセッシングファイルのビューオプションです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、HTML にレンダリングする際のビュー情報を取得します。 |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、HTML にレンダリングする際のビュー情報を取得します。 |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、JPG にレンダリングする際のビュー情報を取得します。 |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、JPG にレンダリングする際のビュー情報を取得します。 |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、PDF にレンダリングする際のビュー情報を取得します。 |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、PNG にレンダリングする際のビュー情報を取得します。 |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを初期化し、PNG にレンダリングする際のビュー情報を取得します。 |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを、[`HtmlViewOptions`](../htmlviewoptions) オブジェクトに基づいて初期化します。 |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを、[`JpgViewOptions`](../jpgviewoptions) オブジェクトに基づいて初期化します。 |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを、[`PdfViewOptions`](../pdfviewoptions) オブジェクトに基づいて初期化します。 |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | [`ViewInfoOptions`](../viewinfooptions) クラスのインスタンスを、[`PngViewOptions`](../pngviewoptions) オブジェクトに基づいて初期化します。 |

### 関連項目

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
