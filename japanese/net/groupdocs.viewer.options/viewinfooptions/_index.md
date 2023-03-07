---
title: ViewInfoOptions
second_title: GroupDocs.Viewer for .NET API リファレンス
description: ビューに関する情報を取得するために使用されるオプションを提供します
type: docs
weight: 570
url: /ja/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

ビューに関する情報を取得するために使用されるオプションを提供します。

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブ ファイルの表示オプション。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 図面表示オプション。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトのフォント. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 電子メール メッセージの表示オプション。 |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | テキスト抽出が有効であることを示します。 |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | 画像の高さ (PNG/JPG へのレンダリングのみ) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メール ストレージ データ ファイルの表示オプション. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | 出力画像の最大高さ (PNG/JPG へのレンダリングのみ) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | 出力画像の最大幅 (PNG/JPG へのレンダリングのみ) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook データ ファイルの表示オプション. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF ドキュメントの表示オプション. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーション処理ドキュメント ビュー オプション. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルの表示オプション. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | コメントのレンダリングを有効にします。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 隠しページのレンダリングを有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | レンダリング ノートを有効にします。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシート ファイルの表示オプション。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキスト ファイルのページ オプションへの分割. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | ドキュメントを処理する Visio ファイルの表示オプション。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | このレンダリング オプションを使用すると、Web ドキュメントをレンダリングするときの出力 HTML/PDF/PNG/JPEG の 外観をカスタマイズできます。 |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | 画像の幅 (PNG/JPG へのレンダリングのみ) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | このレンダリング オプションを使用すると、Word ドキュメントをレンダリングする際に出力 HTML/PDF/PNG/JPEG の 外観をカスタマイズできます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) HTML へのレンダリング時にビューに関する情報を取得するクラス. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) HTML へのレンダリング時にビューに関する情報を取得するクラス. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) JPG. にレンダリングするときにビューに関する情報を取得するクラス |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) JPG. にレンダリングするときにビューに関する情報を取得するクラス |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) PNG にレンダリングするときにビューに関する情報を取得するクラス. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions) PNG にレンダリングするときにビューに関する情報を取得するクラス. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions)に基づくクラス[`HtmlViewOptions`](../htmlviewoptions) object. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions)に基づくクラス[`JpgViewOptions`](../jpgviewoptions) object. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | の新しいインスタンスを初期化します[`ViewInfoOptions`](../viewinfooptions)に基づくクラス[`PngViewOptions`](../pngviewoptions) object. |

### 関連項目

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
