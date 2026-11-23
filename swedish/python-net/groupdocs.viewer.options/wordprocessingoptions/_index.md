---
title: "WordProcessingOptions‑klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Innehåller alternativ för rendering av Word-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Innehåller alternativ för rendering av Word-dokument.

För detaljer, se dokumentationen på https://docs.groupdocs.com/viewer/net/render-word-documents/.

WordProcessingOptions‑typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Initierar alternativ för rendering av ordbehandlingsdokument. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Skapar och returnerar en fullständig djupkopiering av dessa alternativ. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Bestämmer om den angivna [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)‑instansen är lika med denna instans. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Den nedre marginalen på en sida. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Alternativet aktiverar kerning och andra OpenType‑funktioner vid rendering av arabiska, hebreiska, indiska latinska eller kyrilliska skript. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Den horisontella upplösningen för genererade bilder i punkter per tum. Detta alternativ används endast vid rendering av WordProcessing‑dokument till PNG‑ eller JPEG‑format. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Den vänstra marginalen på en sida. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Sidnumreringsplatsen för det inlästa WordProcessing‑dokumentet, som kan tvinga på sidnumrering; som standard är den `WordsPageNumberLocation.not_apply`, vilket lämnar dokumentet oförändrat. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Storleken på utskriftssidan. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Egenskapen möjliggör rendering av spårade ändringar (revisioner). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Den högra marginalen på en sida. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Den övre marginalen på en sida i punkter. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Alternativet inaktiverar navigering från innehållsförteckningen när det är satt till True för HTML‑ eller PDF‑rendering. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Egenskapen bestämmer om fält av vissa typer uppdateras innan WordProcessing‑dokumentet sparas till HTML-, PDF-, PNG- eller JPEG‑format. Standardvärdet är True, vilket innebär att fält uppdateras. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Den vertikala upplösningen för genererade bilder i punkter per tum, som används när WordProcessing-dokument renderas till PNG- eller JPEG-format endast. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
