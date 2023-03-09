---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for .NET API リファレンス
description: ドキュメントを HTML 形式にレンダリングするためのオプションを提供します
type: docs
weight: 330
url: /ja/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

ドキュメントを HTML 形式にレンダリングするためのオプションを提供します。

```csharp
public class HtmlViewOptions : ViewOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | アーカイブ ファイルの表示オプション。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 図面表示オプション。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | ドキュメントで使用されている特定のフォントが見つからない場合に使用されるデフォルトのフォント. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 電子メール メッセージの表示オプション。 |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | 有効にすると、HTML ドキュメントにフォントを追加できなくなります。 |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML ドキュメントから除外するフォント名のリスト。 |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 出力 HTML を印刷用に最適化するかどうかを示します。 |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 出力画像のピクセル単位の高さ。 (単一画像を HTML に変換する場合のみ) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 出力画像の最大高さ (ピクセル単位)。 (単一画像を HTML に変換する場合のみ) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 出力画像の最大幅 (ピクセル単位)。 (単一画像を HTML に変換する場合のみ) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 出力画像の幅 (ピクセル単位)。 (単一画像を HTML に変換する場合のみ) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | メール ストレージ データ ファイルの表示オプション. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML コンテンツと HTML リソースの縮小を有効にします。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook データ ファイルの表示オプション. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF ドキュメントの表示オプション. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | プレゼンテーション処理ドキュメント ビュー オプション. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | プロジェクト管理ファイルの表示オプション. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | コメントのレンダリングを有効にします。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 隠しページのレンダリングを有効にします。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | レンダリング ノートを有効にします。 |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | レスポンシブ レンダリングを有効にします。 レスポンシブ Web ページは、さまざまな画面サイズのデバイスで適切にレンダリングされます。 |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | ドキュメント全体を 1 つの HTML ファイルにレンダリングできるようにします。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | スプレッドシート ファイルの表示オプション。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | テキスト ファイルのページ オプションへの分割. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | ドキュメントを処理する Visio ファイルの表示オプション。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 各ページに適用されるテキスト透かし. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | このレンダリング オプションを使用すると、Web ドキュメントをレンダリングするときの出力 HTML/PDF/PNG/JPEG の 外観をカスタマイズできます。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | このレンダリング オプションを使用すると、Word ドキュメントをレンダリングする際に出力 HTML/PDF/PNG/JPEG の 外観をカスタマイズできます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)リソースが埋め込まれた HTML にレンダリングするためのクラス. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)リソースが埋め込まれた HTML にレンダリングするためのクラス. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)class. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)リソースが埋め込まれた HTML にレンダリングするためのクラス. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)class. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | の新しいインスタンスを初期化します[`HtmlViewOptions`](../htmlviewoptions)外部リソースを使用して HTML にレンダリングするためのクラス. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | ページに時計回りの回転を適用します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | ページの回転。 |

### 関連項目

* class [ViewOptions](../viewoptions)
* 名前空間 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
