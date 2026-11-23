---
title: "Classe EmailOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Contiene opzioni per il rendering dei messaggi email."
type: docs
url: /it/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

Contiene opzioni per il rendering dei messaggi email.

GroupDocs.Viewer supporta la classe EmailOptions che consente di specificare diverse opzioni per il rendering dei messaggi email. Per accedere a queste opzioni, utilizzare la proprietà EmailOptions su una delle seguenti classi di opzioni di visualizzazione, a seconda del formato di output desiderato:

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

Il tipo EmailOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | Inizializza un'istanza della classe [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | Il formato dell'ora (può includere il fuso orario). Se non impostato, viene utilizzato il formato di sistema corrente. |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | La mappatura tra il messaggio email [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) e la rappresentazione testuale del campo. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | La dimensione della pagina di output. |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | L'offset del fuso orario del messaggio. |

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
