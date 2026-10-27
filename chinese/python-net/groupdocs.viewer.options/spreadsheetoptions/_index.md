---
title: "SpreadsheetOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "渲染电子表格的选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

渲染电子表格的选项.

有关详细信息，请参阅 Render spreadsheet files 主题的子条目。

SpreadsheetOptions 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | 初始化一个 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 实例，以将整张工作表渲染为单页。 |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | 初始化一个已配置为按分页符将工作表拆分为多页的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 实例。 |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | 初始化一个仅渲染打印区域的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 类实例。 |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | 初始化一个用于渲染打印区域和分页符的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 类实例。 |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | 初始化一个 SpreadsheetOptions 实例，以将工作表渲染为多页。 |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | 初始化一个 SpreadsheetOptions 实例，以将工作表渲染为多页。 |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | 转换为 PDF 时页面的底部边距。 |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | 在将工作表拆分为多页时，每页包含的列数。 |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | 在将工作表拆分为多页时，每页包含的行数。 |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | 此属性启用对 CSV/TSV 文件分隔符的检测。 |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | 生成图像的水平分辨率（每英寸点数）。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。 |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | 转换为 PDF 时页面的左侧边距。 |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | 该属性启用网格线的渲染。 |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | 该属性启用标题的渲染。 |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | 该属性启用隐藏列的渲染。 |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | 该属性启用隐藏行的渲染。 |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | 将页面转换为 PDF 时的右边距。 |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | 该属性禁用空列的渲染。 |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | 该属性禁用空行的渲染。 |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | 将电子表格文档渲染为 HTML 时的文本溢出模式。默认值是 `TextOverflowMode.OverlayIfNextIsEmpty`，它模拟了默认的 MS Excel 行为。 |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | 将页面转换为 PDF 时的上边距。 |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | 生成图像的垂直分辨率，单位为每英寸点数。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # 在电子表格中启用网格线的渲染。
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
