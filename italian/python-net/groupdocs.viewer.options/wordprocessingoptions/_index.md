---
title: "Classe WordProcessingOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Contiene le opzioni per il rendering dei documenti Word."
type: docs
url: /it/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Contiene le opzioni per il rendering dei documenti Word.

Per i dettagli, consultare la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/render-word-documents/.

Il tipo WordProcessingOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Inizializza le opzioni per il rendering dei documenti di elaborazione testi. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Crea e restituisce una copia profonda completa di queste opzioni. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Determina se l'istanza specificata [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) è uguale a questa istanza. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Il margine inferiore di una pagina. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | L'opzione abilita il kerning e altre funzionalità OpenType durante il rendering di script arabi, ebraici, indiani basati su latino o basati su cirillico. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | La risoluzione orizzontale per le immagini generate in punti per pollice. Questa opzione è usata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Il margine sinistro di una pagina. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | La posizione della numerazione di pagina per il documento WordProcessing caricato, che può applicare forzatamente la numerazione di pagina; per impostazione predefinita è `WordsPageNumberLocation.not_apply`, lasciando intatto il documento. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | La dimensione della pagina di output. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | La proprietà abilita il rendering delle modifiche tracciate (revisioni). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Il margine destro di una pagina. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Il margine superiore di una pagina in punti. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | L'opzione disabilita la navigazione dal sommario quando impostata su True per il rendering HTML o PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | La proprietà determina se i campi di determinati tipi vengono aggiornati prima di salvare il documento WordProcessing in formati HTML, PDF, PNG o JPEG. Il valore predefinito è True, il che significa che i campi vengono aggiornati. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | La risoluzione verticale per le immagini generate in punti per pollice, usata solo durante il rendering di documenti WordProcessing in formati PNG o JPEG. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
