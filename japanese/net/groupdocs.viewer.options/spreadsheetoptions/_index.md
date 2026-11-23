---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "スプレッドシートのレンダリングオプションを含みます。詳細は Render spreadsheet files の子項目（https//docs.groupdocs.com/viewer/net/renderspreadsheets/）をご覧ください。"
type: docs
weight: 530
url: /ja/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

スプレッドシートのレンダリング オプションが含まれています。詳細については、[Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/) トピックの子項目を参照してください。

```csharp
public class SpreadsheetOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | PDF に変換する際のページの下余白を設定します。 |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | ワークシートをページに分割する際、各ページに含める列数です。 |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | ワークシートをページに分割する際、各ページに含める行数です。 |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | 区切り文字を検出します（CSV/TSV ファイル用）。 |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | 生成された画像の水平解像度（dpi）を取得または設定します。このオプションはスプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。 |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | PDF に変換する際のページの左余白を設定します。 |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | グリッドラインのレンダリングを有効にします。 |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | 見出しのレンダリングを有効にします。 |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | 非表示列のレンダリングを有効にします。 |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | 非表示行のレンダリングを有効にします。 |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | PDF に変換する際のページの右余白を設定します。 |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | 空の列のレンダリングを無効にします。 |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | 空の行のレンダリングを無効にします。 |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを設定します。デフォルトは 、MS Excel の既定の動作を模倣します。 |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | PDF に変換する際のページの上余白を設定します。 |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | 生成された画像の垂直解像度（dpi）を取得または設定します。このオプションはスプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | 全シートを1ページにレンダリングするために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | 改ページでページに分割するために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | 印刷領域のみをレンダリングするために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | 印刷領域と改ページをレンダリングするために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | シートをページに分割してレンダリングするために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | シートをページに分割してレンダリングするために、[`SpreadsheetOptions`](../spreadsheetoptions) クラスのインスタンスを初期化します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
