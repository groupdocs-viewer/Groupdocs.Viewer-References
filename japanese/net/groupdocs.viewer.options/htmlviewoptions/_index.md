---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ドキュメントをHTML形式でレンダリングするためのオプションを含みます。詳細はトピック https//docs.groupdocs.com/viewer/net/renderingtohtml/ とその子ページを参照してください。"
type: docs
weight: 320
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

ドキュメントを HTML 形式にレンダリングするオプションが含まれています。詳細については、[topic](https://docs.groupdocs.com/viewer/net/rendering-to-html/) とその子項目を参照してください。

```csharp
public class HtmlViewOptions : ViewOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブファイルのビューオプションです。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD図面のビューオプションです。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントのデフォルトフォントを設定します。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | メールメッセージのビューオプションです。 |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | HTMLドキュメントへのフォント追加を無効にします。 |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTMLドキュメントから除外するフォント名のリストです。 |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 印刷用に出力HTMLの最適化を有効にします。 |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 出力画像の高さ（ピクセル単位）。このプロパティは単一画像をHTMLに変換する場合にのみ利用可能です。 |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 出力画像の最大高さ（ピクセル単位）。このプロパティは単一画像をHTMLに変換する場合にのみ利用可能です。 |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 出力画像の最大幅（ピクセル単位）。このプロパティは単一画像をHTMLに変換する場合にのみ利用可能です。 |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 出力画像の幅（ピクセル単位）。このプロパティは単一画像をHTMLに変換する場合にのみ利用可能です。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メールストレージデータファイルのビューオプションです。 |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTMLコンテンツとHTMLリソースの縮小化を有効にします。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlookデータファイルのビューオプションです。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDFドキュメントのビューオプションです。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーションファイルのビューオプションです。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルのビューオプションです。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | `true` に設定するとコメントの描画が無効になります。デフォルトは `false` で、すべてのコメントが表示されます。 |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | スクリプトを含む入力ドキュメントをレンダリングする際、結果のHTMLドキュメント内のリンクからJavaScriptソースコードを削除できるようにします。デフォルトでは有効です（`true`）。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 非表示ページの描画を有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 一部の形式でノートと注釈の描画を有効にします |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | レスポンシブなレンダリングを有効にします。 |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | ドキュメント全体を1つのHTMLファイルにレンダリングすることを有効にします。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシートファイルのビューオプションです。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキストファイルのビューオプションです。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visioファイルのビューオプションです。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 各ページに適用されるテキスト透かしです。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Webファイルのビューオプションです。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | ワードプロセッシングファイルのビューオプションです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化します。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、埋め込みリソース付きのHTMLにレンダリングします。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、埋め込みリソース付きのHTMLにレンダリングします。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化します。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、埋め込みリソース付きのHTMLにレンダリングします。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化します。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、外部リソース付きのHTMLにレンダリングします。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、外部リソース付きのHTMLにレンダリングします。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化します。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | [`HtmlViewOptions`](../htmlviewoptions) クラスのインスタンスを初期化し、外部リソース付きのHTMLにレンダリングします。 |
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
