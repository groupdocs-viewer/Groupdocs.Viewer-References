---
title: "WordProcessingOptions‑klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Bevat opties voor het renderen van Word-documenten."
type: docs
url: /nl/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Bevat opties voor het renderen van Word-documenten.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/render-word-documents/.

Het type WordProcessingOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Initialiseert opties voor het renderen van tekstverwerkingsdocumenten. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Maakt een volledige diepe kopie van deze opties en retourneert deze. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Bepaalt of de opgegeven [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) instantie gelijk is aan deze instantie. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | De onderste marge van een pagina. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | De optie schakelt kerning en andere OpenType-functies in bij het renderen van Arabische, Hebreeuwse, Indiaanse op Latijn gebaseerd, of Cyrillisch gebaseerde scripts. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | De horizontale resolutie voor gegenereerde afbeeldingen in dots per inch. Deze optie wordt alleen gebruikt bij het renderen van WordProcessing-documenten naar PNG- of JPEG-formaten. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | De linkermarge van een pagina. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | De paginanummeringslocatie voor het geladen WordProcessing-document, die paginanummering kan afdwingen; standaard is het `WordsPageNumberLocation.not_apply`, waardoor het document ongewijzigd blijft. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | De grootte van de uitvoerpagina. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | De eigenschap schakelt het renderen van bijgehouden wijzigingen (revisies) in. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | De rechtermarge van een pagina. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | De bovenmarge van een pagina in punten. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | De optie schakelt navigatie vanuit de inhoudsopgave uit wanneer deze op True is ingesteld voor HTML- of PDF-rendering. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | De eigenschap bepaalt of velden van bepaalde typen worden bijgewerkt voordat het WordProcessing-document wordt opgeslagen naar HTML-, PDF-, PNG- of JPEG-formaten. Standaard is True, wat betekent dat velden worden bijgewerkt. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | De verticale resolutie voor gegenereerde afbeeldingen in dots per inch, gebruikt bij het renderen van WordProcessing-documenten naar PNG- of JPEG-formaten alleen. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
