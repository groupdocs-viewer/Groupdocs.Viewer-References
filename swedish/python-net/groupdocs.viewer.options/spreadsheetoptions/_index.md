---
title: "SpreadsheetOptions-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Alternativen för att rendera kalkylblad."
type: docs
url: /sv/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Alternativen för att rendera kalkylblad.

För detaljer, se underavsnitten till ämnet Render spreadsheet files.

SpreadsheetOptions-typen visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Initierar en [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑instans för att rendera hela bladet på en sida. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Initierar en [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑instans konfigurerad för att dela upp kalkylblad i sidor vid sidbrytningar. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Initierar en instans av [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑klassen för att endast rendera utskriftsområden. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Initierar en instans av klassen [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) för rendering av utskriftsområden och sidbrytningar. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Initierar en SpreadsheetOptions-instans för rendering av ett blad till sidor. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Initierar en SpreadsheetOptions-instans för rendering av ett blad till sidor. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | Den nedre marginalen på en sida vid konvertering till PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Antalet kolumner att inkludera på varje sida när kalkylbladet delas upp i sidor. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Antalet rader att inkludera på varje sida när kalkylbladet delas upp i sidor. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | Egenskapen möjliggör detektering av en separator för CSV/TSV-filer. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | Den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | Den vänstra marginalen på en sida vid konvertering till PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | Egenskapen möjliggör rendering av rutnätlinjer. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | Egenskapen möjliggör rendering av rubriker. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | Egenskapen möjliggör rendering av dolda kolumner. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | Egenskapen möjliggör rendering av dolda rader. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | Den högra marginalen på en sida vid konvertering till PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | Egenskapen inaktiverar rendering av tomma kolumner. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | Egenskapen inaktiverar rendering av tomma rader. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Textöversvämningsläget för rendering av kalkylbladdokument till HTML. Standard är `TextOverflowMode.OverlayIfNextIsEmpty`, vilket efterliknar standardbeteendet i MS Excel. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | Den övre marginalen på en sida vid konvertering till PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | Den vertikala upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av kalkylblad till PNG- eller JPEG-format. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Aktivera rendering av rutnätlinjer i kalkylbladet.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
