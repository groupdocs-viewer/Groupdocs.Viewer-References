---
title: "SpreadsheetOptions‑Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Optionen zum Rendern von Tabellenkalkulationen."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Die Optionen zum Rendern von Tabellenkalkulationen.

Für Details siehe die Unterpunkte des Themas Render spreadsheet files.

Der Typ SpreadsheetOptions stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Initialisiert eine [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Instanz zum Rendern des gesamten Blatts auf einer Seite. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Initialisiert eine [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Instanz, die so konfiguriert ist, Arbeitsblätter anhand von Seitenumbrüchen in Seiten zu splitten. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Initialisiert eine Instanz der [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Klasse, um ausschließlich die Druckbereiche zu rendern. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Initialisiert eine Instanz der [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Klasse, um Druckbereiche und Seitenumbrüche zu rendern. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Initialisiert eine SpreadsheetOptions‑Instanz zum Rendern eines Blatts in Seiten. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Initialisiert eine SpreadsheetOptions‑Instanz zum Rendern eines Blatts in Seiten. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | Der untere Rand einer Seite beim Konvertieren in PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Die Spaltenanzahl, die pro Seite beim Aufteilen des Arbeitsblatts in Seiten enthalten sein soll. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Die Zeilenanzahl, die pro Seite beim Aufteilen des Arbeitsblatts in Seiten enthalten sein soll. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | Die Eigenschaft ermöglicht die Erkennung eines Trennzeichens für CSV/TSV-Dateien. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | Die horizontale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | Der linke Rand einer Seite beim Konvertieren zu PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | Die Eigenschaft ermöglicht das Rendern von Gitternetzlinien. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | Die Eigenschaft ermöglicht das Rendern von Überschriften. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | Die Eigenschaft ermöglicht das Rendern versteckter Spalten. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | Die Eigenschaft ermöglicht das Rendern versteckter Zeilen. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | Der rechte Rand einer Seite beim Konvertieren zu PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | Die Eigenschaft deaktiviert das Rendern leerer Spalten. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | Die Eigenschaft deaktiviert das Rendern leerer Zeilen. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Der Textüberlaufmodus für das Rendern von Tabellenkalkulationsdokumenten in HTML. Der Standard ist `TextOverflowMode.OverlayIfNextIsEmpty`, der das Standardverhalten von MS Excel nachahmt. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | Der obere Rand einer Seite beim Konvertieren zu PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | Die vertikale Auflösung für erzeugte Bilder in Punkten pro Zoll. Diese Option wird nur beim Rendern von Tabellenkalkulationen in PNG- oder JPEG-Formate verwendet. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Rendern von Gitternetzlinien in der Tabellenkalkulation aktivieren.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
