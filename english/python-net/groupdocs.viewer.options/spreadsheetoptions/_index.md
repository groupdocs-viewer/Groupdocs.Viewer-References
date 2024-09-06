---
title: SpreadsheetOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 220
url: /python-net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Contains options for rendering spreadsheets. For details, see children of the

The SpreadsheetOptions type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|count_rows_per_page|The rows count to include on each page when splitting the worksheet into pages.|
|count_columns_per_page|The columns count to include on each page when splitting the worksheet into pages.|
|render_grid_lines|Enables grid lines rendering.|
|skip_empty_rows|Disables empty rows rendering.|
|skip_empty_columns|Disables empty columns rendering.|
|render_hidden_rows|Enables hidden rows rendering.|
|render_headings|Enables headings rendering.|
|render_hidden_columns|Enables hidden columns rendering.|
|detect_separator|Detect a separator (for CSV/TSV files).|
|left_margin|Sets the left margin of a page when converting to PDF.|
|right_margin|Sets the right margin of a page when converting to PDF.|
|top_margin|Sets the top margin of a page when converting to PDF.|
|bottom_margin|Sets the bottom margin of a page when converting to PDF.|
|text_overflow_mode|Sets the text overflow mode for rendering spreadsheet documents into HTML.|
## Methods
| Name | Description |
| :- | :- |
|for_split_sheet_into_pages(count_rows_per_page)|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for rendering sheet into pages.|
|for_split_sheet_into_pages(count_rows_per_page, count_columns_per_page)|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for rendering sheet into pages.|
|for_one_page_per_sheet()|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for rendering the whole sheet into one page.|
|for_rendering_print_area()|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for rendering the print areas only.|
|for_rendering_print_area_and_page_breaks()|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for rendering print areas and page breaks.|
|for_rendering_by_page_breaks()|Initializes an instance of the [SpreadsheetOptions](/python-net/groupdocs.viewer.options/spreadsheetoptions/) class for splitting to pages by page breaks.|

### See Also

* namespace [groupdocs.viewer.options](/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

