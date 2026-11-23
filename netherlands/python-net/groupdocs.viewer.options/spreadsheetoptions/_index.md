---
title: "SpreadsheetOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De opties voor het renderen van spreadsheets."
type: docs
url: /nl/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

De opties voor het renderen van spreadsheets.

Zie voor details de subonderwerpen van het onderwerp Render spreadsheet‑bestanden.

Het type SpreadsheetOptions bevat de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Initialiseert een [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) instantie voor het renderen van het volledige blad op één pagina. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Initialiseert een [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) instantie geconfigureerd om werkbladen te splitsen in pagina's op paginabreaks. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Initialiseert een instantie van de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) klasse voor het alleen renderen van de afdrukgebieden. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Initialiseert een instantie van de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) klasse voor het renderen van afdrukgebieden en paginabreaks. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Initialiseert een SpreadsheetOptions‑instantie voor het renderen van een blad in pagina's. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Initialiseert een SpreadsheetOptions‑instantie voor het renderen van een blad in pagina's. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | De onderste marge van een pagina bij het converteren naar PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Het aantal kolommen dat moet worden opgenomen op elke pagina bij het splitsen van het werkblad in pagina's. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Het aantal rijen dat moet worden opgenomen op elke pagina bij het splitsen van het werkblad in pagina's. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | De eigenschap maakt detectie van een scheidingsteken voor CSV/TSV‑bestanden mogelijk. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | De horizontale resolutie voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van spreadsheets naar PNG‑ of JPEG‑formaten. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | De linkermarge van een pagina bij het converteren naar PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | De eigenschap maakt het renderen van rasterlijnen mogelijk. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | De eigenschap maakt het renderen van kopteksten mogelijk. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | De eigenschap maakt het renderen van verborgen kolommen mogelijk. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | De eigenschap maakt het renderen van verborgen rijen mogelijk. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | De rechter marge van een pagina bij het converteren naar PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | De eigenschap schakelt het renderen van lege kolommen uit. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | De eigenschap schakelt het renderen van lege rijen uit. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | De tekst‑overloopmodus voor het renderen van spreadsheet‑documenten naar HTML. Standaard is `TextOverflowMode.OverlayIfNextIsEmpty`, wat het standaardgedrag van MS Excel nabootst. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | De bovenmarge van een pagina bij het converteren naar PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | De verticale resolutie voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van spreadsheets naar PNG- of JPEG-formaten. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Schakel het renderen van rasterlijnen in de spreadsheet in.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
