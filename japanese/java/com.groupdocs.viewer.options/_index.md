---
title: "com.groupdocs.viewer.options"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "このパッケージは、文書をレンダリングする際の追加オプションを指定するためのクラスを提供します。"
type: docs
weight: 19
url: /ja/java/com.groupdocs.viewer.options/
---

このパッケージは、文書をレンダリングする際の追加オプションを指定するためのクラスを提供します。


さまざまなドキュメント形式のレンダリング、権限とセキュリティ設定の定義に関するオプションが含まれます、
透かしプロパティの指定、およびビューに関する情報の取得。

このパッケージの主なクラスは次のとおりです：

* [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - Provides options for rendering archive files.
* [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - Provides options for rendering PDF documents.
* [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - Provides options for rendering word processing documents.


GroupDocs.Viewer のロギングシステムの構成とログメッセージ処理のカスタマイズに関する詳細は、
こちらの [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/) を参照してください。



## クラス

| クラス | 説明 |
| --- | --- |
| [ArchiveOptions](../com.groupdocs.viewer.options/archiveoptions) | アーカイブファイルのレンダリングオプションを提供します。 |
| [ArchiveSecurityOptions](../com.groupdocs.viewer.options/archivesecurityoptions) | アーカイブ抽出プロセスを制限するために使用できるクラスです。 |
| [BaseViewOptions](../com.groupdocs.viewer.options/baseviewoptions) | 基本的なレンダリングオプションを含みます。 |
| [CadOptions](../com.groupdocs.viewer.options/cadoptions) | CAD 図面のレンダリングオプションを提供します。 |
| [EmailOptions](../com.groupdocs.viewer.options/emailoptions) | メールメッセージのレンダリングオプションを提供します。 |
| [FileName](../com.groupdocs.viewer.options/filename) | アーカイブ内のファイル名を表します。 |
| [HtmlViewOptions](../com.groupdocs.viewer.options/htmlviewoptions) | ドキュメントを HTML 形式でレンダリングするオプションを提供します。 |
| [JpgViewOptions](../com.groupdocs.viewer.options/jpgviewoptions) | ドキュメントを JPG 形式でレンダリングするオプションを提供します。 |
| [LoadOptions](../com.groupdocs.viewer.options/loadoptions) | ファイルを開く際に使用されるオプションを提供します。 |
| [MailStorageOptions](../com.groupdocs.viewer.options/mailstorageoptions) | メールストレージ（Lotus Notes、MBox）データファイルのレンダリングオプションを提供します。 |
| [OutlookOptions](../com.groupdocs.viewer.options/outlookoptions) | Outlook データファイルのレンダリングオプションを提供します。 |
| [PdfOptimizationOptions](../com.groupdocs.viewer.options/pdfoptimizationoptions) | このクラスを使用して、出力 PDF ファイルに適用する PDF 最適化オプションを指定します。 |
| [PdfOptions](../com.groupdocs.viewer.options/pdfoptions) | PDF ドキュメントのレンダリングオプションを提供します。 |
| [PdfViewOptions](../com.groupdocs.viewer.options/pdfviewoptions) | ドキュメントを PDF 形式にレンダリングするためのオプションを提供します。 |
| [Permissions](../com.groupdocs.viewer.options/permissions) | PDF ドキュメントの権限を定義します。 |
| [PngViewOptions](../com.groupdocs.viewer.options/pngviewoptions) | ドキュメントを PNG 形式にレンダリングするオプションを提供します。 |
| [PresentationOptions](../com.groupdocs.viewer.options/presentationoptions) | プレゼンテーションのレンダリングオプションを提供します。 |
| [ProjectManagementOptions](../com.groupdocs.viewer.options/projectmanagementoptions) | プロジェクト管理ファイルのレンダリングオプションを提供します。 |
| [SearchHighlightOptions](../com.groupdocs.viewer.options/searchhighlightoptions) | ドキュメント内のテキストを検索およびハイライトするオプションを提供します。ロードされた [Viewer](../com.groupdocs.viewer/viewer) クラス用です。 |
| [Security](../com.groupdocs.viewer.options/security) | PDF ドキュメントのセキュリティオプションを提供します。 |
| [Size](../com.groupdocs.viewer.options/size) | 透かしのサイズを含みます。 |
| [SpreadsheetOptions](../com.groupdocs.viewer.options/spreadsheetoptions) | スプレッドシートのレンダリングオプションを提供します。 |
| [TextOptions](../com.groupdocs.viewer.options/textoptions) | テキストファイルをページに分割するオプションです。 |
| [Tile](../com.groupdocs.viewer.options/tile) | 描画領域を表します。 |
| [ViewInfoOptions](../com.groupdocs.viewer.options/viewinfooptions) | ビューに関する情報取得に使用されるオプションを提供します。 |
| [ViewOptions](../com.groupdocs.viewer.options/viewoptions) | レンダリングオプションを含みます。 |
| [VisioRenderingOptions](../com.groupdocs.viewer.options/visiorenderingoptions) | Visio ドキュメントのレンダリングオプションを含みます。 |
| [Watermark](../com.groupdocs.viewer.options/watermark) | テキスト透かしを表します。 |
| [WordProcessingOptions](../com.groupdocs.viewer.options/wordprocessingoptions) | ワードプロセッシングドキュメントのレンダリングオプションを提供します。 |

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IMaxSizeOptions](../com.groupdocs.viewer.options/imaxsizeoptions) | 画像サイズ制限オプションインターフェイスです。 |

## 列挙型

| 列挙体 | 説明 |
| --- | --- |
| [Field](../com.groupdocs.viewer.options/field) | メールメッセージのフィールド（例：From、To、Subject など）を表します。 |
| [ImageQuality](../com.groupdocs.viewer.options/imagequality) | PDF 文書に含まれる出力 HTML の画像の品質。 |
| [PageSize](../com.groupdocs.viewer.options/pagesize) | ページのサイズ。 |
| [Position](../com.groupdocs.viewer.options/position) | 透かしの位置を定義します。 |
| [Resolution](../com.groupdocs.viewer.options/resolution) | 画像の解像度を設定するオプションを提供します：出力ドキュメント。 |
| [Rotation](../com.groupdocs.viewer.options/rotation) | ページの回転角度（時計回り）を含みます。 |
| [TextOverflowMode](../com.groupdocs.viewer.options/textoverflowmode) | スプレッドシート文書を HTML にレンダリングする際のテキストオーバーフローモードを定義します。 |
| [TimeUnit](../com.groupdocs.viewer.options/timeunit) | プロジェクト期間の時間単位。 |
| [WordsPageNumberLocation](../com.groupdocs.viewer.options/wordspagenumberlocation) | 読み込まれた WordProcessing 文書にページ番号付与を強制的に適用するかどうか、適用する場合はページ番号の配置場所を制御します。 |
