---
title: "Classe PdfViewOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le opzioni per il rendering dei documenti in formato PDF."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfviewoptions/
is_root: false
weight: 170
---


## PdfViewOptions class

Rappresenta le opzioni per il rendering dei documenti in formato PDF.

Per i dettagli, vedere la documentazione.

Il tipo PdfViewOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream) | Inizializza un'istanza di [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream-release_file_stream) | Inizializza una nuova istanza di PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#file_stream_factory) | Inizializza un'istanza di PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/) | Inizializza un'istanza di PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#output_file_path) | Inizializza un'istanza della classe [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Applica la rotazione in senso orario a una pagina. (eredita da [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (eredita da [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [image_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/) | L'altezza di un'immagine di output in pixel. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) | L'altezza massima di un'immagine di output in pixel. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) | La larghezza massima di un'immagine di output in pixel. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/) | La larghezza dell'immagine di output in pixel. |
| [pdf_optimization_options](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/pdf_optimization_options/) | La proprietà pdf_optimization_options fornisce l'accesso a un'istanza di [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/) che riduce la dimensione del file PDF di output applicando tecniche di ottimizzazione. |
| [security](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/security/) | Le opzioni di sicurezza per il documento PDF di output. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Le opzioni di visualizzazione dei file di archivio. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Le opzioni di visualizzazione dei disegni CAD. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Il carattere predefinito per un documento utilizzato durante il rendering quando un carattere richiesto è mancante. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Le opzioni di visualizzazione dei messaggi email. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Le opzioni di visualizzazione dei file di dati di archiviazione della posta. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Le opzioni di visualizzazione dei file di dati Microsoft Outlook. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | La rotazione della pagina. (eredita da [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | Le opzioni di visualizzazione del documento PDF. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | Le opzioni di visualizzazione dei file di presentazione. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | Le opzioni di visualizzazione dei file di gestione progetti. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | La proprietà disabilita il rendering dei commenti quando impostata su True. Per impostazione predefinita è False, quindi tutti i commenti sono visualizzati. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | La proprietà abilita o disabilita il rendering dei commenti. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | La proprietà abilita il rendering delle pagine nascoste. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | La proprietà abilita il rendering di note e annotazioni per alcuni formati. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | Le opzioni di visualizzazione dei file di fogli di calcolo. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | Le opzioni di testo per il rendering dei file di testo. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Le opzioni di visualizzazione dei file Visio. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | La filigrana di testo da applicare a ogni pagina. (eredita da [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Le opzioni di visualizzazione dei file Web. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Le opzioni di visualizzazione dei file di elaborazione testi. (eredita da [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Guides
Guide operative che utilizzano `PdfViewOptions`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
