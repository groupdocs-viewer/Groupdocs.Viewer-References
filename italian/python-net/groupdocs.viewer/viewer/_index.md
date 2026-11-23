---
title: "Classe Viewer"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta la classe principale che controlla il processo di rendering del documento."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Rappresenta la classe principale che controlla il processo di rendering del documento.

Il tipo Viewer espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Inizializza una nuova istanza di Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Inizializza una nuova istanza della classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Inizializza una nuova istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Inizializza una nuova istanza di Viewer. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Rilascia lo stream del file e le risorse interne gestite. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Restituisce tutti i font utilizzati nel documento caricato, inclusi i font incorporati e i font di sistema installati sul sistema operativo. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Restituisce gli allegati contenuti nel documento. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Restituisce informazioni sul file, come il tipo di file e un flag che indica se il file è crittografato. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Restituisce informazioni specifiche della vista e del documento. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Salva il file allegato nello stream `destination`. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Esegue una ricerca di testo e evidenzia il testo trovato nel documento caricato in base alle opzioni fornite. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Crea una vista di tutte le pagine del documento. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Crea una vista di pagine specifiche del documento. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Crea una vista di pagine specifiche del documento. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Renderizza DOCX in HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Renderizza PDF in PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Guide operative che utilizzano `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Vedi anche
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
