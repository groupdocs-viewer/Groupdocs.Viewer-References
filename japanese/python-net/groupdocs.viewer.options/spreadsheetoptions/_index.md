---
title: "SpreadsheetOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "スプレッドシートのレンダリングオプション。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

スプレッドシートのレンダリングオプション。

詳細については、Render spreadsheet files トピックの子項目をご覧ください。

SpreadsheetOptions 型は以下のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | 全シートを 1 ページにレンダリングするための [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) インスタンスを初期化します。 |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | ページ区切りでワークシートをページに分割するように構成された [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) インスタンスを初期化します。 |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | 印刷領域のみをレンダリングするための [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) クラスのインスタンスを初期化します。 |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | 印刷領域とページ区切りをレンダリングするための [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) クラスのインスタンスを初期化します。 |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | シートをページに分割してレンダリングするための SpreadsheetOptions インスタンスを初期化します。 |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | シートをページに分割してレンダリングするための SpreadsheetOptions インスタンスを初期化します。 |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | PDF に変換する際のページの下余白です。 |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | ワークシートをページに分割する際、各ページに含める列数です。 |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | ワークシートをページに分割する際、各ページに含める行数です。 |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | このプロパティは、CSV/TSV ファイルの区切り文字の検出を可能にします。 |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | 生成された画像の水平解像度（dpi）。このオプションは、スプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。 |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | PDF に変換する際のページの左余白です。 |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | このプロパティはグリッド線の描画を有効にします。 |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | このプロパティは見出しの描画を有効にします。 |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | このプロパティは非表示列の描画を有効にします。 |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | このプロパティは非表示行の描画を有効にします。 |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | PDF に変換する際のページの右余白です。 |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | このプロパティは空の列の描画を無効にします。 |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | このプロパティは空の行の描画を無効にします。 |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | スプレッドシート ドキュメントを HTML に描画する際のテキストオーバーフローモードです。デフォルトは `TextOverflowMode.OverlayIfNextIsEmpty` で、既定の MS Excel の動作を模倣します。 |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | PDF に変換する際のページの上余白です。 |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | 生成された画像の垂直解像度（dpi）です。このオプションはスプレッドシートを PNG または JPEG 形式に描画する場合にのみ使用されます。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # スプレッドシートでグリッド線の描画を有効にします。
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
