---
title: "Classe SpreadsheetOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Le opzioni per il rendering dei fogli di calcolo."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Le opzioni per il rendering dei fogli di calcolo.

Per i dettagli, consulta le voci figlio dell'argomento Render spreadsheet files.

Il tipo SpreadsheetOptions espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Inizializza un'istanza di [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) per il rendering dell'intero foglio in una sola pagina. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Inizializza un'istanza di [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurata per suddividere i fogli di lavoro in pagine tramite interruzioni di pagina. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Inizializza un'istanza della classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) per il rendering solo delle aree di stampa. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Inizializza un'istanza della classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) per il rendering delle aree di stampa e delle interruzioni di pagina. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Inizializza un'istanza di SpreadsheetOptions per il rendering di un foglio in pagine. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Inizializza un'istanza di SpreadsheetOptions per il rendering di un foglio in pagine. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | Il margine inferiore di una pagina durante la conversione in PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Il numero di colonne da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Il numero di righe da includere in ogni pagina quando si suddivide il foglio di lavoro in pagine. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | La proprietà consente il rilevamento di un separatore per file CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | La risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formato PNG o JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | Il margine sinistro di una pagina durante la conversione in PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | La proprietà consente il rendering delle linee della griglia. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | La proprietà consente il rendering delle intestazioni. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | La proprietà consente il rendering delle colonne nascoste. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | La proprietà consente il rendering delle righe nascoste. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | Il margine destro di una pagina durante la conversione in PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | La proprietà disabilita il rendering delle colonne vuote. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | La proprietà disabilita il rendering delle righe vuote. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | La modalità di overflow del testo per il rendering dei documenti di foglio di calcolo in HTML. L'impostazione predefinita è `TextOverflowMode.OverlayIfNextIsEmpty`, che imita il comportamento predefinito di MS Excel. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | Il margine superiore di una pagina durante la conversione in PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | La risoluzione verticale per le immagini generate in punti per pollice. Questa opzione è utilizzata solo durante il rendering dei fogli di calcolo in formati PNG o JPEG. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Abilita il rendering delle linee della griglia nel foglio di calcolo.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
